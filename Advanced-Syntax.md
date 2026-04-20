## Goto

**Keyword:** `goto`

Moves the importer to a different action container before continuing execution. Syntax varies depending on the container you'd like to open.

**Container Types**

| Type | Syntax | Description |
| ---- | ------ | ----------- |
| Function | `goto function <name>` | **name:** Function name |
| Event | `goto event <name>` | **name:** Event name |
| Command | `goto command <name>` | **name:** Command name |
| NPC | `goto npc <name>` | **name:** Arbitrary NPC's name (manual selection required) |
| Action Button | `goto button <name>` | **name:** Arbitrary button name (manual selection required) |
| Action Pad | `goto pad <name>` | **name:** Arbitrary action pad name (manual selection required) |
| Region | `goto region <name> <entry/exit>` | **name:** Region name<br/>**entry/exit:** "Entry Actions" or "Exit Actions" |
| GUI | `goto gui <name> <slot>` | **name:** GUI title/name<br/>**slot:** The slot of the GUI |


***


## Javascript Interpolation

Allows dynamic values to be inserted using JavaScript-style expressions.

**Syntax**

```
{<expression>}
```

**Description**

- Expressions inside `{}` are evaluated before compilation
- Can be used anywhere a string or number is expected
- Useful for generating dynamic names, values, or repeated patterns

**Examples**

```
chat {"Hello " + "World"}
var score = {5 * 10}
loop i 5 {
    chat {"Loop #" + i}
}
```


***


## Loops

**Keyword:** `loop`

**Parameters**
| Parameter | Type | Description |
| --------- | ---- | ------------|
| index | String | The name of a variable you can use in the loop to refer to the current iteration |
| count | Number | A whole number, specifying how many times to loop for |
| actions | Action | A list of actions separated by line |

**Syntax**

```
loop [index] <count> {
    <actions>
}
```

**Examples**

```
loop i 5 {
    chat Loop i
}
```

```
loop 3 {
    sound random.orb 1 1 player
    pause 5
}
```

**Notes**

- `index` can be omitted
- If provided, it starts at `0` and increments each iteration
- Loops are expanded at compile time (not runtime)


***


## Null Parameters

`null` can replace any parameter to represent an explicitly empty or unused parameter. This is used when a parameter is required syntactically but you do not want to provide a value. This Prevents shifting of arguments in positional syntax. The importer will just not touch a parameter marked as null, so the value will remain the default provided by Housing.

**Examples**

```
giveItem diamond_sword false null false
```

```
hasItem diamond null null 1
```


***


## Placeholder Shortcuts

Provides shorthand access to commonly used placeholders. This can simplify long or complex placeholder names. Expands to full placeholder values during compilation.

**Types**
| Shortcut | Expands to |
| -------- | ---------- |
| `var <name>` | `%var.player/<name>%` |
| `globalvar <name>` | `%var.global/<name>%` |
| `teamvar <name> <team>` | `%var.team/<name> <team>%` |
| `randomint <inclusive_origin> <exclusive_bound>` | `%random.int/<inclusive_origin> <exclusive_bound>%` |
| `health` | `%player.health%` |
| `maxHealth` | `%player.maxhealth%` |
| `hunger` | `%player.hunger%` |
| `locX` | `%player.location.x%` |
| `locY` | `%player.location.y%` |
| `locZ` | `%player.location.z%` |
| `unix` | `%date.unix%` |


***


## Compiler Shortcuts

Defines reusable shorthand expressions that expand during compilation.

**Keyword:** `define`

**Syntax**

```
define <name> <replacement>
```

**Description**

- Creates a macro that replaces all future occurrences of `<name>` with `<replacement>`
- Acts similarly to `#define` in C/C++
- Expansion happens at compile time
- Only applies when the shortcut is not inside quotes

**Examples**

```c
define kills stat kills
kills increment 1
// compiles to
stat kills increment 1
```

```c
define coins %var.player/coins%
chat coins
// compiles to
chat %var.player/coins%
```

**Notes**

- Shortcuts are purely textual replacements, not variables
- Quoted usage disables expansion
