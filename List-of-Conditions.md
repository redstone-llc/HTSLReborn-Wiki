## Block Type

**Keyword:** `blockType`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| block | String | Path to the block's NBT file |
| match_type_only | Boolean | Whether to match only the block type |

**Syntax**

```
blockType <item> <match_type_only>
```


***


## Damage Amount

**Keyword:** `damageAmount`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | String/Operator | Comparison operator (==, <, <=, >, >=, etc.) |
| value | Number | The damage value |

**Syntax**

```
damageAmount <operator> <value>
```


***


## Damage Cause

**Keyword:** `damageCause`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| cause | String | The cause of damage (`Poison`, etc.) |

**Syntax**

```
damageCause <cause>
```


***


## Doing Parkour

**Keyword:** `doingParkour`

**Syntax**

```
doingParkour
```


***


## Fishing Environment

**Keyword:** `fishingEnv`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| environment | String | The fishing environment type (`Water` or `Lava`) |

**Syntax**

```
fishingEnv <environment>
```


***


## Global Variable Requirement

**Keyword:** `globalvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | The global variable name |
| operator | String/Operator | Comparison operator |
| value | Value | Value to compare against |
| fallback | Value | Default value if unset |

**Syntax**

```
globalvar <identifier> <operator> <value> <fallback>
```


***


## Has Item

**Keyword:** `hasItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | String | Path to the item's NBT file |
| mode | String | Matching mode (`metadata`, `type`, etc.) |
| slot | String | Inventory slot |
| amount | String | Required amount |

**Syntax**

```
hasItem <item> <mode> <slot> <amount>
```


***


## Has Potion Effect

**Keyword:** `hasPotion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| effect | String | The potion effect |

**Syntax**

```
hasPotion <effect>
```


***


## Is Item

**Keyword:** `isItem`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| item | String | Path to the item's NBT file |
| mode | String | Matching mode (`metadata`, `type`, etc.) |
| slot | String | Inventory slot |
| amount | String | Required amount |

**Syntax**

```
isItem <item> <mode> <slot> <amount>
```


***


## Is Sneaking

**Keyword:** `isSneaking`

**Syntax**

```
isSneaking
```


***


## Max Health Requirement

**Keyword:** `maxHealth`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | String/Operator | Comparison operator |
| value | Number | Health value |

**Syntax**

```
maxHealth <operator> <value>
```


***


## Placeholder Number Requirement

**Keyword:** `placeholder`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| placeholder | String | A placeholder |
| operator | String/Operator | Comparison operator |
| value | Number | Value to compare |

**Syntax**

```
placeholder <placeholder> <operator> <value>
```


***


## Player Flying

**Keyword:** `isFlying`

**Syntax**

```
isFlying
```


***


## Player Health

**Keyword:** `health`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | String/Operator | Comparison operator |
| value | Number | Health value |

**Syntax**

```
health <operator> <value>
```


***


## Player Hunger

**Keyword:** `hunger`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| operator | String/Operator | Comparison operator |
| value | Number | Hunger value |

**Syntax**

```
hunger <operator> <value>
```


***


## Player Variable Requirement

**Keyword:** `var`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | Variable name |
| operator | String/Operator | Comparison operator |
| value | Value | Value to compare |
| fallback | Value | Default value if unset |

**Syntax**

```
var <identifier> <operator> <value> <fallback>
```


***


## Portal Type

**Keyword:** `portal`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| type | String | Portal type (`End Portal` or `Nether Portal`) |

**Syntax**

```
portal <type>
```


***


## PvP Enabled

**Keyword:** `canPvp`

**Syntax**

```
canPvp
```


***


## Required Gamemode

**Keyword:** `gamemode`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| mode | String | Required gamemode (`Creative`, `Survival`, or `Adventure`) |

**Syntax**

```
gamemode <mode>
```


***


## Required Group

**Keyword:** `hasGroup`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| group | String | Group name |
| include_higher | Boolean | Include higher priority groups |

**Syntax**

```
hasGroup <group> <include_higher>
```


***


## Required Permission

**Keyword:** `hasPermission`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| permission | String | Permission name (`Fly`, etc.) |

**Syntax**

```
hasPermission <permission>
```


***


## Required Team

**Keyword:** `hasTeam`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| team | String | Team name |

**Syntax**

```
hasTeam <team>
```


***


## Team Variable Requirement

**Keyword:** `teamvar`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| identifier | String | Variable name |
| team | String | Team name |
| operator | String/Operator | Comparison operator |
| value | Value | Value to compare |
| fallback | Value | Default value if unset |

**Syntax**

```
teamvar <identifier> <team> <operator> <value> <fallback>
```


***


## Within Region

**Keyword:** `inRegion`

**Parameters**

| Parameter | Type | Description |
| --------- | ---- | ------------|
| region | String | Region name |

**Syntax**

```
inRegion <region>
```


***