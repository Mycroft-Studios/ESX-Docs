# IsVehicleEmpty

```lua
ESX.Game.IsVehicleEmpty(vehicle)
```

Returns A bool for if the Vehicle has no players inside.

## Example

```lua
local vehicle = ESX.Game.GetVehicleInDirection()

if ESX.Game.IsVehicleEmpty(vehicle) then
  ESX.ShowNotification('Vehicle Is empty')
end

```
