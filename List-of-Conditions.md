## Block Type

**Keyword:** `blockType`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| block | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Path to the block's NBT file |
| match_type_only | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to match only the block type |

**Syntax**

```
blockType <item> <match_type_only>
```

<br>

***

<br>

## Damage Amount

**Keyword:** `damageAmount`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | The damage value |

**Syntax**

```
damageAmount <operator> <value>
```

<br>

***

<br>

## Damage Cause

**Keyword:** `damageCause`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| cause | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | The cause of damage (`Poison`, etc.) |

**Syntax**

```
damageCause <cause>
```

<br>

***

<br>

## Doing Parkour

**Keyword:** `doingParkour`

**Syntax**

```
doingParkour
```

<br>

***

<br>

## Fishing Environment

**Keyword:** `fishingEnv`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| environment | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | The fishing environment type (`Water` or `Lava`) |

**Syntax**

```
fishingEnv <environment>
```

<br>

***

<br>

## Global Variable Requirement

**Keyword:** `globalvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | The global variable name |
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Value to compare against |
| fallback | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Default value if unset |

**Syntax**

```
globalvar <identifier> <operator> <value> <fallback>
```

<br>

***

<br>

## Has Item

**Keyword:** `hasItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Path to the item's NBT file |
| mode | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Matching mode (`metadata`, `type`, etc.) |
| slot | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Inventory slot |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Required amount |

**Syntax**

```
hasItem <item> <mode> <slot> <amount>
```

<br>

***

<br>

## Has Potion Effect

**Keyword:** `hasPotion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | The potion effect |

**Syntax**

```
hasPotion <effect>
```

<br>

***

<br>

## Is Item

**Keyword:** `isItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Path to the item's NBT file |
| mode | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Matching mode (`metadata`, `type`, etc.) |
| slot | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Inventory slot |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Required amount |

**Syntax**

```
isItem <item> <mode> <slot> <amount>
```

<br>

***

<br>

## Is Sneaking

**Keyword:** `isSneaking`

**Syntax**

```
isSneaking
```

<br>

***

<br>

## Max Health Requirement

**Keyword:** `maxHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Health value |

**Syntax**

```
maxHealth <operator> <value>
```

<br>

***

<br>

## Placeholder Number Requirement

**Keyword:** `placeholder`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| placeholder | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | A placeholder |
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Value to compare against |

**Syntax**

```
placeholder <placeholder> <operator> <value>
```

<br>

***

<br>

## Player Flying

**Keyword:** `isFlying`

**Syntax**

```
isFlying
```

<br>

***

<br>

## Player Health

**Keyword:** `health`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Health value |

**Syntax**

```
health <operator> <value>
```

<br>

***

<br>

## Player Hunger

**Keyword:** `hunger`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Hunger value |

**Syntax**

```
hunger <operator> <value>
```

<br>

***

<br>

## Player Variable Requirement

**Keyword:** `var`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Variable name |
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Value to compare against |
| fallback | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Default value if unset |

**Syntax**

```
var <identifier> <operator> <value> <fallback>
```

<br>

***

<br>

## Portal Type

**Keyword:** `portal`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| type | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Portal type (`End Portal` or `Nether Portal`) |

**Syntax**

```
portal <type>
```

<br>

***

<br>

## PvP Enabled

**Keyword:** `canPvp`

**Syntax**

```
canPvp
```

<br>

***

<br>

## Required Gamemode

**Keyword:** `gamemode`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| mode | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Required gamemode (`Creative`, `Survival`, or `Adventure`) |

**Syntax**

```
gamemode <mode>
```

<br>

***

<br>

## Required Group

**Keyword:** `hasGroup`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| group | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Group name |
| include_higher | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Include higher priority groups |

**Syntax**

```
hasGroup <group> <include_higher>
```

<br>

***

<br>

## Required Permission

**Keyword:** `hasPermission`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| permission | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Permission name (`Fly`, etc.) |

**Syntax**

```
hasPermission <permission>
```

<br>

***

<br>

## Required Team

**Keyword:** `hasTeam`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| team | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Team name |

**Syntax**

```
hasTeam <team>
```

<br>

***

<br>

## Team Variable Requirement

**Keyword:** `teamvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Variable name |
| team | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Team name |
| operator | [Conditional Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#conditional-operator) | The method of comparison |
| value | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Value to compare against |
| fallback | [Value](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#value) | Default value if unset |

**Syntax**

```
teamvar <identifier> <team> <operator> <value> <fallback>
```

<br>

***

<br>

## Within Region

**Keyword:** `inRegion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| region | [String](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#string) | Region name |

**Syntax**

```
inRegion <region>
```

<br>

***

<br>