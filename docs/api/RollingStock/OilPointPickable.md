# OilPointPickable Class

**Namespace:** `RollingStock`
**Source:** `OilPointPickable.cs`

## Declaration

```csharp
public class OilPointPickable : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TooltipInfo` | `TooltipInfo` | public | - |

## Methods

### DisplayOiled

```csharp
private float DisplayOiled()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `hotboxEffect` | `HotboxEffect` | private | - |
| `_car` | `Car` | private | - |
| `_cachedTooltipText` | `string` | private | - |
| `_cachedTooltipTextTime` | `float` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_pendingOil` | `float` | private | - |
| `_cachedTooFast` | `bool` | private | - |
| `_cachedOilInt` | `int` | private | - |
| `_cachedHasHotbox` | `bool` | private | - |
| `_displayOiled` | `float` | private | - |
| `_displayOiledTimeout` | `float` | private | - |
| `TooFast` | `bool` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

