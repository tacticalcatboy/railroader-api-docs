# NightLightController Class

**Namespace:** `Effects`
**Source:** `NightLightController.cs`

## Declaration

```csharp
public class NightLightController : MonoBehaviour
```

## Methods

### SetOn

```csharp
private void SetOn(bool on)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `light` | `Light` | public | - |
| `threshold` | `float` | public | - |
| `bulbRenderer` | `Renderer` | public | - |
| `baseColor` | `Color` | public | - |
| `materialIntensity` | `float` | public | - |
| `_lightIntensityMultiplier` | `float` | private | - |
| `_parameter` | `float` | private | - |
| `_scheduleHandle` | `IDisposable` | private | - |
| `_materialPropertyBlock` | `MaterialPropertyBlock` | private | - |

