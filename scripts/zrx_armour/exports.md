# Exports

## Client

### hasArmour()

Checks if there is an active armour.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local hasArmour = exports.zrx_armour:hasArmour()

if hasArmour then
    print('yes')
else
    print('no')
end
```

***

### displayArmour(state)

Enables/Disables the armour vest.

<mark style="color:blue;">**Parameters:**</mark>\
**state** - `bool` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_armour:displayArmour(false)
```

***

## Server

### hasCooldown(player)

Checks if a player has an active cooldown.

<mark style="color:blue;">**Parameters:**</mark>\
**player** - `number` - The player server id

<mark style="color:green;">**Returns:**</mark>\
`false/number` - Number is the os.time() timestamp

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_armour:hasCooldown(1)

if cooldown then
    print('yes')
else
    print('no')
end
```
