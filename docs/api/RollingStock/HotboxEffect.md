# HotboxEffect Class

**Namespace:** `RollingStock`
**Source:** `HotboxEffect.cs`

## Declaration

```csharp
public class HotboxEffect : MonoBehaviour
```

## Methods

### UpdateForHotbox

```csharp
private void UpdateForHotbox(bool hotbox)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `smokeEffect` | `VisualEffect` | private | - |
| `light` | `Light` | private | - |
| `_observer` | `IDisposable` | private | - |
| `_index` | `int` | private | - |
| `_carHash` | `int` | private | - |
| `_lightIntensity` | `float` | private | - |
| `_firstUpdateHotbox` | `bool` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_hotbox` | `bool` | private | - |
| `_effectGameObject` | `GameObject` | private | - |
| `_smoke` | `SmokeEffectWrapper` | private | - |
| `_smokeRate0` | `float` | private | - |
| `_smokeVelocity0` | `float` | private | - |
| `_car` | `Car` | private | - |

