# Exports

## Client

### hasKey(plate, forceOwner)

Checks if a player has a vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**plate** - `string` - The vehicle plate\
**forceOwner** - `boolean` - Has to be the vehicle owner?

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or false

<mark style="color:orange;">**Example:**</mark>

```lua
local state = exports.zrx_carlock:hasKey(vehicle, false)

if state then
    print('yes')
else
    print('no')
end
```

***

### giveKey(plate)

Gives the vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**plate** - `string` - The vehicle plate

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_carlock:giveKey('ABC123')
```

***

### removeKey(plate)

Removes the vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**plate** - `string` - The vehicle plate

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_carlock:removeKey('ABC123')
```

***

### openKeyMenu()

Opens the givekey menu.

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_carlock:openKeyMenu()
```

***

## Server

### hasKey(player, plate, forceOwner)

Checks if a player has a vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**player** - `number` - The player server id\
**plate** - `string` - The vehicle plate\
**forceOwner** - `boolean` - Has to be the vehicle owner?

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or false

<mark style="color:orange;">**Example:**</mark>

```lua
local state = exports.zrx_carlock:hasKey(1, vehicle, false)

if state then
    print('yes')
else
    print('no')
end
```

***

### giveKey(player, plate)

Gives the vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**player** - `number` - The player server id\
**plate** - `string` - The vehicle plate

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_carlock:giveKey(1, 'ABC123')
```

***

### removeKey(player, plate)

Removes the vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**player** - `number` - The player server id\
**plate** - `string` - The vehicle plate

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_carlock:removeKey(1, 'ABC123')
```

***

### updatePlate(oldPlate, newPlate)

Removes the vehicle key.

<mark style="color:blue;">**Parameters:**</mark>\
**oldPlate** - `string` - The vehicle old plate\
**newPlate** - `string` - The vehicle new plate

<mark style="color:orange;">**Example:**</mark>

```lua
local oldPlate = 'ABC123'
local newPlate = '123ABC'

exports.zrx_carlock:updatePlate(oldPlate, newPlate)
```
