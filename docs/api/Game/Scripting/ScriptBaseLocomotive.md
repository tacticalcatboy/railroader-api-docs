# ScriptBaseLocomotive Class

**Namespace:** `Game.Scripting`
**Source:** `ScriptBaseLocomotive.cs`

## Declaration

```csharp
public class ScriptBaseLocomotive : ScriptCar
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `throttle` | `float` | public | - |

## Methods

### set_control_ae_waypoint

```csharp
public void set_control_ae_waypoint(ScriptLocation location, int speed, string coupleCarId = null)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_locomotive` | `BaseLocomotive` | private | `readonly` |
| `_controls` | `LocomotiveControlHelper` | private | `readonly` |
| `AutoEngineerOrdersHelper` | `AutoEngineerOrdersHelper` | private | - |
| `AutoEngineer` | `AutoEngineer` | private | - |

