## Apply Inventory Layout

**Keyword:** `applyLayout`

This would apply a layout

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| name | String | The name of the inventory layout |

**Syntax**

```
applyLayout <name>
```


***


## Apply Potion Effect

**Keyword:** `applyPotion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | String | The type of effect to apply to the player |
| duration | Integer | How long the effect should last, in seconds |
| level | Integer | The amplifier of the effect |
| override | Boolean | Whether to override an existing effect of the same type |
| hide_particles | Boolean | Whether to hide particle effects produced by the effect |

**Syntax**

```
applyPotion <effect> <duration> <level> <override> <hide_particles>
```


***


## Balance Player Team

**Keyword:** `balanceTeam`

**Syntax**

```
balanceTeam
```


***


## Cancel Event

**Keyword:** `cancelEvent`

Cancels an event.

**Syntax**

```
cancelEvent
```


***


## Change Global Variable

**Keyword:** `globalvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the global variable |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate by |
| unset | Boolean | Automatic unset |

**Syntax**

```
globalvar <identifier> <operation> <amount> <unset>
```


***


## Change health

**Keyword:** `changeHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate the player's health by |

**Syntax**

```
changeHealth <operation> <amount>
```


***


## Change Hunger Level

**Keyword:** `hungerLevel`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate the player's hunger by |

**Syntax**

```
hungerLevel <operation> <amount>
```

***


## Change Max Health

**Keyword:** `maxHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate the player's maximum health by |

**Syntax**

```
maxHealth <operation> <amount>
```


***


## Change Player Group

**Keyword:** `changePlayerGroup`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The group to apply to the player |
| demotion_protection | Boolean | Prevent this action from demoting a player with a higher group priority |

**Syntax**

```
changePlayerGroup <identifier> <demotion_protection>
```


***


## Change Player Variable

**Keyword:** `var`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the player variable |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate by |
| unset | Boolean | Automatic unset |

**Syntax**

```
var <identifier> <operation> <amount> <unset>
```


***


## Change Team Variable

**Keyword:** `teamVar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the team variable |
| team | String | The name of the team |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Number | The amount to manipulate by |
| unset | Boolean | Automatic unset |

**Syntax**

```
teamvar <identifier> <team> <operation> <amount> <unset>
```


***


## Clear All Potion Effects

**Keyword:** `clearEffects`

**Syntax**

```
clearEffects
```


***


## Close Menu

**Keyword:** `closeMenu`

**Syntax**

```
closeMenu
```


***


## Conditional

**Keyword:** `if`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| or | String/Boolean | `true` or `or` for OR mode, `false` or `and` or omitted for AND mode. |
| conditions | String | A list of conditions, comma separated (optional) |
| if_actions | Actions | A list of actions to execute if true, line separated |
| else_actions | Actions | A list of actions to execute if false, line separated |

#### Syntax

```
if <or> (<conditions>) {
    <if_actions>
} else {
    <else_actions>
}
```


***


## Display Action Bar

**Keyword:** `actionBar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | String | The message to send in the action bar |

**Syntax**

```
actionBar <message>
```


***


## Display Menu

**Keyword:** `displayMenu`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name/title of the menu |

**Syntax**

```
displayMenu <identifier>
```


***


## Display Title

**Keyword:** `title`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | String | The message to send in a title |

**Syntax**

```
title <message>
```


***


## Enchant Held Item

**Keyword:** `enchant`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | String | The message to send in a title |
| level | Integer | The level of the enchantment |

**Syntax**

```
enchant <effect> <level>
```


***


## Exit

**Keyword:** `exit`

**Syntax**

```
exit
```


***


## Fail Parkour

**Keyword:** `failParkour`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| reason | String | The message to send in the parkour failed message |

**Syntax**

```
failParkour <reason>
```


***


## Full Heal

**Keyword:** `fullHeal`

**Syntax**

```
fullHeal
```


***


## Give Experience Levels

**Keyword:** `xpLevel`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| amount | Integer | The number of XP levels to give the player |

**Syntax**

```
xpLevel <amount>
```


***


## Give Item

**Keyword:** `giveItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | String | Path to the item's NBT file |
| allow_multiple | Boolean | Whether the player can receive multiple of the item |
| slot | String | The inventory slot to place the item in |
| replace | Boolean | Whether to replace an existing item in the slot |

**Syntax**

```
giveItem <item> <allow_multiple> <slot> <replace>
```


***


## Go to House Spawn

**Keyword:** `houseSpawn`

**Syntax**

```
houseSpawn
```


***


## Kill Player

**Keyword:** `kill`

**Syntax**

```
kill
```


***


## Parkour Checkpoint

**Keyword:** `parkCheck`

**Syntax**

```
parkCheck
```


***


## Pause Execution

**Keyword:** `pause`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| ticks | Integer | The number of ticks to pause execution |

**Syntax**

```
pause <ticks>
```


***


## Play Sound

**Keyword:** `sound`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| sound | String | The sound to play |
| volume | Float | The volume of the sound |
| pitch | Float | The pitch of the sound |
| location | String | The location where the sound plays |

**Syntax**

```
sound <sound> <volume> <pitch> <location>
```


***


## Remove Item

**Keyword:** `removeItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | String | Path to the item's NBT file |

**Syntax**

```
removeItem <item>
```


***


## Reset Inventory

**Keyword:** `resetInventory`

**Syntax**

```
resetInventory
```


***


## Send Chat Message

**Keyword:** `chat`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | String | The message to send |

**Syntax**

```
chat <message>
```


***


## Send to Lobby

**Keyword:** `lobby`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| lobby | String | The lobby name |

**Syntax**

```
lobby <lobby>
```


***


## Set Compass Target

**Keyword:** `compassTarget`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | String | The type of location (`house_spawn`, `current_location`, `invokers_location`, or `custom_coordinates "x y z"`)  |

**Syntax**

```
compassTarget <location>
```


***


## Set Gamemode

**Keyword:** `gamemode`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| mode | String | The gamemode to set |

**Syntax**

```
gamemode <mode>
```


***


## Set Player Team

**Keyword:** `setTeam`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| team | String | The team name |

**Syntax**

```
setTeam <team>
```


***


## Teleport Player

**Keyword:** `tp`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | String | The type of location (`house_spawn`, `current_location`, `invokers_location`, or `custom_coordinates "x y z"`)  |
| safe | Boolean | Prevent teleporting inside blocks |

**Syntax**

```
tp <location> <safe>
```


***


## Trigger Function

**Keyword:** `function`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| name | String | The function name |
| global | Boolean | Whether to run for all players |

**Syntax**

```
function <name> <global>
```


***


## Consume Held Item

**Keyword:** `consumeItem`

**Syntax**

```
consumeItem
```


***


## Drop Item

**Keyword:** `dropItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | String | Path to the item's NBT file |
| location | String | The drop location |
| natural | Boolean | Whether the drop is natural |
| no_merge | Boolean | Prevent merging with other items |
| prioritize_player | Boolean | Prioritize giving to player |
| fallback_inventory | Boolean | Return to inventory if needed |

**Syntax**

```
dropItem <item> <location> <natural> <no_merge> <prioritize_player> <fallback_inventory>
```


***


## Change Velocity

**Keyword:** `changeVelocity`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| x | Number | Velocity on X axis |
| y | Number | Velocity on Y axis |
| z | Number | Velocity on Z axis |

**Syntax**

```
changeVelocity <x> <y> <z>
```


***


## Launch to Target

**Keyword:** `launchTarget`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | String | The type of location (`house_spawn`, `current_location`, `invokers_location`, or `custom_coordinates "x y z"`)  |
| strength | Float | Launch strength |

**Syntax**

```
launchTarget <location> <coordinates> <strength>
```


***


## Set Player Weather

**Keyword:** `playerWeather`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| weather | String | The weather type (`Sunny`, ...) |

**Syntax**

```
playerWeather <weather>
```


***


## Set Player Time

**Keyword:** `playerTime`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| time | Integer | The time value |

**Syntax**

```
playerTime <time>
```


***


## Toggle Nametag Display

**Keyword:** `displayNametag`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| visible | Boolean | Whether the nametag is visible |

**Syntax**

```
displayNametag <visible>
```


***