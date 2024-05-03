# Exports

## Client

### hasCooldown()

Checks if there is an active cooldown.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local cooldown = exports.zrx_repairkit:hasCooldown()

if cooldown then
    print('yes')
else
    print('no')
end
```

***

### isBusy()

Checks if there is an active action.

<mark style="color:green;">**Returns:**</mark>\
`true/false` - True or False

<mark style="color:orange;">**Example:**</mark>

```lua
local isBusy = exports.zrx_repairkit:isBusy()

if isBusy then
    print('yes')
else
    print('no')
end
```
