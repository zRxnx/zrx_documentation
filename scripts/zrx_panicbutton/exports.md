# Exports

## Client

### hasCooldown()

Checks if there is an active cooldown.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_panicbutton:hasCooldown()

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### activeBlips()

Returns all active blips.

<mark style="color:green;">**Returns:**</mark>\
`table` - All active blips

<mark style="color:orange;">**Example:**</mark>

```lua
local blips = exports.zrx_panicbutton:activeBlips()

print(json.encode(blips, { indent = true })
```

***

## Server

### activeBlips()

Returns all active blips.

<mark style="color:green;">**Returns:**</mark>\
`table` - All active blips

<mark style="color:orange;">**Example:**</mark>

```lua
local blips = exports.zrx_personalmenu:activeBlips()

print(json.encode(blips, { indent = true })
```
