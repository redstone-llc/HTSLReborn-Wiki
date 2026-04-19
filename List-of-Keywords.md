## Apply Inventory Layout

**Keyword:** `applyLayout`

This would apply a layout

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| name | String | The name of the inventory layout |

#### Syntax

```
applyLayout <name>
```


***


## Apply Potion Effect

**Keyword:** `applyPotion`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | String | The type of effect to apply to the player |
| duration | Integer | How long the effect should last, in seconds |
| level | Integer | The amplifier of the effect |
| override | Boolean | Whether to override an existing effect of the same type |
| hide_particles | Boolean | Whether to hide particle effects produced by the effect |

#### Syntax

```
applyPotion <effect> <duration> <level> <override> <hide_particles>
```


***


## Balance Player Team

**Keyword:** `balanceTeam`

#### Syntax

```
balanceTeam
```


***


## Cancel Event

**Keyword:** `cancelEvent`

Cancels an event.

#### Syntax

```
cancelEvent
```


***


## Change Global Variable

**Keyword:** `globalvar`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the global variable |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate by |
| unset | Boolean | Automatic unset |

#### Syntax

```
globalvar <identifier> <operation> <amount> <unset>
```


***


## Change health

**Keyword:** `changeHealth`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate the player's health by |

#### Syntax

```
changeHealth <operation> <amount>
```


***


## Change Hunger Level

**Keyword:** `hungerLevel`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate the player's hunger by |

#### Syntax

```
hungerLevel <operation> <amount>
```

***


## Change Max Health

**Keyword:** `maxHealth`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate the player's maximum health by |

#### Syntax

```
maxHealth <operation> <amount>
```


***


## Change Player Group

**Keyword:** `changePlayerGroup`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The group to apply to the player |
| demotion_protection | Boolean | Prevent this action from demoting a player with a higher group priority |

#### Syntax

```
changePlayerGroup <identifier> <demotion_protection>
```


***


## Change Player Variable

**Keyword:** `var`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the player variable |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate by |
| unset | Boolean | Automatic unset |

#### Syntax

```
var <identifier> <operation> <amount> <unset>
```


***


## Change Team Variable

**Keyword:** `teamVar`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name of the team variable |
| team | String | The name of the team |
| operation | String/Operator | The method of manipulation. Supports string-based descriptors like `increment` and operators like `+=` |
| amount | Integer | The amount to manipulate by |
| unset | Boolean | Automatic unset |

#### Syntax

```
teamvar <identifier> <team> <operation> <amount> <unset>
```


***


## Clear All Potion Effects

**Keyword:** `clearEffects`

#### Syntax

```
clearEffects
```


***


## Close Menu

**Keyword:** `closeMenu`

#### Syntax

```
closeMenu
```


***


## Display Action Bar

**Keyword:** `actionBar`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | String | The message to send in the action bar |

#### Syntax

```
actionBar <message>
```


***


## Display Menu

**Keyword:** `displayMenu`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The name/title of the menu |

#### Syntax

```
displayMenu <identifier>
```


***


## Display Title

**Keyword:** `title`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| message | String | The message to send in a title |

#### Syntax

```
title <message>
```


***


## Enchant Held Item

**Keyword:** `enchant`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | String | The message to send in a title |
| level | Integer | The level of the enchantment |

#### Syntax

```
enchant <effect> <level>
```


***


## Exit

**Keyword:** `exit`

#### Syntax

```
exit
```


***


## Fail Parkour

**Keyword:** `failParkour`

#### Parameters

| Parameter | Type | Description |
| --------- | ---- | ------------|
| reason | String | The message to send in the parkour failed message |

#### Syntax

```
failParkour <reason>
```


***


## Full Heal

**Keyword:** `fullHeal`

#### Syntax

```
fullHeal
```


***