# Exports

## Server

### hasCooldown()

Checks if there is an active cooldown.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_blackmarket:hasCooldown()

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### hasCooldown(player)

Checks if a player has an active cooldown.

<mark style="color:blue;">**Parameters:**</mark>\
**player** - `number` - The player server id

<mark style="color:green;">**Returns:**</mark>\
`false/number` - Number is the os.time() timestamp

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_blackmarket:hasCooldown(1)

if cooldown then
    print('yes')
else
    print('no')
end
```
