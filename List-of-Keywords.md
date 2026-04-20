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


***


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
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the global variable |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

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
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's health by |

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
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's hunger by |

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
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate the player's maximum health by |

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
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The group to apply to the player |
| demotion_protection | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prevent this action from demoting a player with a higher group priority |

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
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the player variable |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

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
| identifier | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the team variable |
| team | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The name of the team |
| operation | [Assignment Operator](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#assignment-operator) | The method of manipulation |
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The amount to manipulate by |
| unset | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Automatic unset |

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


***


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


***


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


***


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


***


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
| reason | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send in the parkour failed message |

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
| amount | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The number of XP levels to give the player |

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
| item | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | Path to the item's NBT file |
| allow_multiple | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether the player can receive multiple of the item |
| slot | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The inventory slot to place the item in |
| replace | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to replace an existing item in the slot |

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
| ticks | [Number](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#number) | The number of ticks to pause execution |

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
| sound | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The sound to play |
| volume | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | The volume of the sound |
| pitch | [Number](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#number) | The pitch of the sound |
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location where the sound plays |

**Syntax**

```
sound <sound> <volume> <pitch> <location>
```


***


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


***


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
| message | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The message to send |

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
| lobby | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The lobby name |

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
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The lotation to point the compass to (does not support yaw/pitch) |

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
| mode | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The gamemode to set |

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
| team | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The team name |

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
| location | [Location](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#location) | The location to teleport the player to |
| safe | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Prevent teleporting inside blocks |

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
| name | [String](https://github.com/redstone-llc/HTSLReborn/wiki/List-of-Parameter-Types#string) | The function name |
| global | [Boolean](https://github.com/redstone-llc/HTSLReborn-Wiki/blob/main/List-of-Parameter-Types.md#boolean) | Whether to run for all players |

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


***


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


***


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


***


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


***


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


***


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


***
