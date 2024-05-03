# Exports

## Client

### openMenu()

Opens the personalmenu.

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_personalmenu:openMenu()
```

***

### hasCooldown()

Checks if there is an active cooldown.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_personalmenu:hasCooldown()

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### getConfig()

Returns the config.

<mark style="color:green;">**Returns:**</mark>\
`table` - Returns the config

<mark style="color:orange;">**Example:**</mark>

```lua
local config = exports.zrx_personalmenu:getConfig()

print(json.encode(config, { indent = true })
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
local cooldown = exports.zrx_personalmenu:hasCooldown(1)

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### getConfig()

Returns the config.

<mark style="color:green;">**Returns:**</mark>\
`table` - Returns the config

<mark style="color:orange;">**Example:**</mark>

```lua
local config = exports.zrx_personalmenu:getConfig()

print(json.encode(config, { indent = true })
```
