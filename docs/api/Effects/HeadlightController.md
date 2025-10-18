# HeadlightController Class

**Namespace:** `Effects`
**Source:** `HeadlightController.cs`

## Declaration

```csharp
public class HeadlightController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LightEnabled` | `bool` | public | - |

## Methods

### ValueForState

```csharp
private float ValueForState(State theState)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `state` | `State` | public | - |
| `speedOn` | `float` | public | - |
| `speedOff` | `float` | public | - |
| `dimValue` | `float` | public | - |
| `filamentRenderer` | `Renderer` | public | - |
| `reflector` | `Transform` | public | - |
| `light` | `Light` | public | - |
| `emissiveLightProfile` | `EmissiveLightProfile` | public | - |
| `_camera` | `Camera` | private | - |
| `_parameter` | `float` | private | - |
| `_lightParameter` | `float` | private | - |
| `_zPosition0` | `float` | private | - |
| `_xScale0` | `float` | private | - |
| `_filamentMaterial` | `Material` | private | - |
| `SunLevel` | `float` | private | `static` |

