# Exports

## Client

### activeBlips()

Returns all active blips.

<mark style="color:green;">**Returns:**</mark>\
`table` - All active blips

<mark style="color:orange;">**Example:**</mark>

```lua
local blips = exports.zrx_restrictedzone:activeBlips()

print(json.encode(blips, { indent = true })
```

***

### hasCooldown()

Checks if there is an active cooldown.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_restrictedzone:hasCooldown()

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### Server

### activeBlips()

Returns all active blips.

<mark style="color:green;">**Returns:**</mark>\
`table` - All active blips

<mark style="color:orange;">**Example:**</mark>

```lua
local blips = exports.zrx_restrictedzone:activeBlips()

print(json.encode(blips, { indent = true })
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
local cooldown = exports.zrx_restrictedzone:hasCooldown(1)

if cooldown then
    print('yes')
else
    print('no')
end
```
