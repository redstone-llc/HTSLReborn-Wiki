## Apply Inventory Layout

**Keyword:** `applyLayout`

This would apply a layout

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| name | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the inventory layout |

**Syntax**

```
applyLayout <name>
```

<br>

***

<br>

## Apply Potion Effect

**Keyword:** `applyPotion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The type of effect to apply to the player |
| duration | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | How long the effect should last, in seconds |
| level | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amplifier of the effect |
| override | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to override an existing effect of the same type |
| hide_particles | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to hide particle effects produced by the effect |

**Syntax**

```
applyPotion <effect> <duration> <level> <override> <hide_particles>
```

<br>

***

<br>

## Balance Player Team

**Keyword:** `balanceTeam`

**Syntax**

```
balanceTeam
```

<br>

***

<br>

## Cancel Event

**Keyword:** `cancelEvent`

Cancels an event.

**Syntax**

```
cancelEvent
```

<br>

***

<br>

## Change Global Variable

**Keyword:** `globalvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the global variable |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

**Syntax**

```
globalvar <identifier> <operation> <amount> <unset>
```

<br>

***

<br>

## Change health

**Keyword:** `changeHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's health by |

**Syntax**

```
changeHealth <operation> <amount>
```

<br>

***

<br>

## Change Hunger Level

**Keyword:** `hungerLevel`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's hunger by |

**Syntax**

```
hungerLevel <operation> <amount>
```
<br>

***

<br>

## Change Max Health

**Keyword:** `maxHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's maximum health by |

**Syntax**

```
maxHealth <operation> <amount>
```

<br>

***

<br>

## Change Player Group

**Keyword:** `changePlayerGroup`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The group to apply to the player |
| demotion_protection | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prevent this action from demoting a player with a higher group priority |

**Syntax**

```
changePlayerGroup <identifier> <demotion_protection>
```

<br>

***

<br>

## Change Player Variable

**Keyword:** `var`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the player variable |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

**Syntax**

```
var <identifier> <operation> <amount> <unset>
```

<br>

***

<br>

## Change Team Variable

**Keyword:** `teamVar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the team variable |
| team | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the team |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

**Syntax**

```
teamvar <identifier> <team> <operation> <amount> <unset>
```

<br>

***

<br>

## Clear All Potion Effects

**Keyword:** `clearEffects`

**Syntax**

```
clearEffects
```

<br>

***

<br>

## Close Menu

**Keyword:** `closeMenu`

**Syntax**

```
closeMenu
```

<br>

***

<br>

## Conditional

**Keyword:** `if`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| mode | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | What logical mode to evaluate the condition on (`or` for OR mode, `and` or omitted for AND mode) |
| conditions | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | A list of conditions, comma separated (optional) |
| if_actions | [Action](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#action) | A list of actions to execute if true, line separated |
| else_actions | [Action](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#action) | A list of actions to execute if false, line separated |

**Syntax**

```
if <mode> (<conditions>) {
    <if_actions>
} else {
    <else_actions>
}
```

<br>

***

<br>

## Display Action Bar

**Keyword:** `actionBar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send in the action bar |

**Syntax**

```
actionBar <message>
```

<br>

***

<br>

## Display Menu

**Keyword:** `displayMenu`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name/title of the menu |

**Syntax**

```
displayMenu <identifier>
```

<br>

***

<br>

## Display Title

**Keyword:** `title`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send in a title |

**Syntax**

```
title <message>
```

<br>

***

<br>

## Enchant Held Item

**Keyword:** `enchant`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send in a title |
| level | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The level of the enchantment |

**Syntax**

```
enchant <effect> <level>
```

<br>

***

<br>

## Exit

**Keyword:** `exit`

**Syntax**

```
exit
```

<br>

***

<br>

## Fail Parkour

**Keyword:** `failParkour`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| reason | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send in the parkour failed message |

**Syntax**

```
failParkour <reason>
```

<br>

***

<br>

## Full Heal

**Keyword:** `fullHeal`

**Syntax**

```
fullHeal
```

<br>

***

<br>

## Give Experience Levels

**Keyword:** `xpLevel`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The number of XP levels to give the player |

**Syntax**

```
xpLevel <amount>
```

<br>

***

<br>

## Give Item

**Keyword:** `giveItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | Path to the item's NBT file |
| allow_multiple | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether the player can receive multiple of the item |
| slot | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The inventory slot to place the item in |
| replace | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to replace an existing item in the slot |

**Syntax**

```
giveItem <item> <allow_multiple> <slot> <replace>
```

<br>

***

<br>

## Go to House Spawn

**Keyword:** `houseSpawn`

**Syntax**

```
houseSpawn
```

<br>

***

<br>

## Kill Player

**Keyword:** `kill`

**Syntax**

```
kill
```

<br>

***

<br>

## Parkour Checkpoint

**Keyword:** `parkCheck`

**Syntax**

```
parkCheck
```

<br>

***

<br>

## Pause Execution

**Keyword:** `pause`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| ticks | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The number of ticks to pause execution |

**Syntax**

```
pause <ticks>
```

<br>

***

<br>

## Play Sound

**Keyword:** `sound`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| sound | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The sound to play |
| volume | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | The volume of the sound |
| pitch | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | The pitch of the sound |
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location where the sound plays |

**Syntax**

```
sound <sound> <volume> <pitch> <location>
```

<br>

***

<br>

## Random Action

**Keyword:** `random`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| actions | [Action](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#action) | List of actions to choose from (line separated) |

**Syntax**

```
random {
    <actions>
}
```

<br>

***

<br>

## Remove Item

**Keyword:** `removeItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | Path to the item's NBT file |

**Syntax**

```
removeItem <item>
```

<br>

***

<br>

## Reset Inventory

**Keyword:** `resetInventory`

**Syntax**

```
resetInventory
```

<br>

***

<br>

## Send Chat Message

**Keyword:** `chat`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send |

**Syntax**

```
chat <message>
```

<br>

***

<br>

## Send to Lobby

**Keyword:** `lobby`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| lobby | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The lobby name |

**Syntax**

```
lobby <lobby>
```

<br>

***

<br>

## Set Compass Target

**Keyword:** `compassTarget`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The lotation to point the compass to (does not support yaw/pitch) |

**Syntax**

```
compassTarget <location>
```

<br>

***

<br>

## Set Gamemode

**Keyword:** `gamemode`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| mode | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The gamemode to set |

**Syntax**

```
gamemode <mode>
```

<br>

***

<br>

## Set Player Team

**Keyword:** `setTeam`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| team | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The team name |

**Syntax**

```
setTeam <team>
```

<br>

***

<br>

## Teleport Player

**Keyword:** `tp`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location to teleport the player to |
| safe | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prevent teleporting inside blocks |

**Syntax**

```
tp <location> <safe>
```

<br>

***

<br>

## Trigger Function

**Keyword:** `function`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| name | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The function name |
| global | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to run for all players |

**Syntax**

```
function <name> <global>
```

<br>

***

<br>

## Consume Held Item

**Keyword:** `consumeItem`

**Syntax**

```
consumeItem
```

<br>

***

<br>

## Drop Item

**Keyword:** `dropItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | Path to the item's NBT file |
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location to drop the item at (does not support yaw/pitch) |
| natural | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether the drop is natural |
| no_merge | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prevent merging with other items |
| prioritize_player | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prioritize giving to player |
| fallback_inventory | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Return to inventory if needed |

**Syntax**

```
dropItem <item> <location> <natural> <no_merge> <prioritize_player> <fallback_inventory>
```

<br>

***

<br>

## Change Velocity

**Keyword:** `changeVelocity`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| x | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | Velocity on X axis |
| y | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | Velocity on Y axis |
| z | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | Velocity on Z axis |

**Syntax**

```
changeVelocity <x> <y> <z>
```

<br>

***

<br>

## Launch to Target

**Keyword:** `launchTarget`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location to launch the player to  |
| strength | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | Launch strength |

**Syntax**

```
launchTarget <location> <coordinates> <strength>
```

<br>

***

<br>

## Set Player Weather

**Keyword:** `playerWeather`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| weather | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The weather type (`Sunny`, ...) |

**Syntax**

```
playerWeather <weather>
```

<br>

***

<br>

## Set Player Time

**Keyword:** `playerTime`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| time | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The time value |

**Syntax**

```
playerTime <time>
```

<br>

***

<br>

## Toggle Nametag Display

**Keyword:** `displayNametag`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| visible | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether the nametag is visible |

**Syntax**

```
displayNametag <visible>
```

<br>

***

<br>