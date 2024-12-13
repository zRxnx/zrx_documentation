# Exports

## Client

### GetPlayerUIDfromSID(serverId)

Gets the UniqueID from a ServerID.

<mark style="color:blue;">**Parameters:**</mark>\
**serverId** - `number` - The player server id

<mark style="color:green;">**Returns:**</mark>\
`number` - The player unique id

<mark style="color:orange;">**Example:**</mark>

```lua
local svid = GetPlayerServerId(PlayerId())
local targetUID = exports.zrx_uniqueid:GetPlayerUIDfromSID(svid)

print(targetUID)
```

***

### GetPlayerSIDfromUID(uniqueId)

Gets the ServerID from an UniqueID.

<mark style="color:blue;">**Parameters:**</mark>\
**uniqueId** - `number` - The player unique id

<mark style="color:green;">**Returns:**</mark>\
`number` - The player server id

<mark style="color:orange;">**Example:**</mark>

```lua
local targetID = exports.zrx_uniqueid:GetPlayerSIDfromUID(10)

print(targetID)
```

***

## Server

### GetPlayerUIDfromSID(uniqueId)

Gets the ServerID from an UniqueID.

<mark style="color:blue;">**Parameters:**</mark>\
**uniqueId** - `number` - The player unique id

<mark style="color:green;">**Returns:**</mark>\
`number` - The player server id

<mark style="color:orange;">**Example:**</mark>

```lua
local targetID = exports.zrx_uniqueid:GetPlayerUIDfromSID(source)

print(targetID)
```

***

### ChangePlayerUID(old\_uid, new\_uid)

Changes the player UniqueID.

<mark style="color:blue;">**Parameters:**</mark>\
**old\_uid** - `number` - The player current unique id\
**new\_uid** - `number` - The player new unique id

<mark style="color:orange;">**Example:**</mark>

```lua
exports.zrx_uniqueid:ChangePlayerUID(69, 100)
```
