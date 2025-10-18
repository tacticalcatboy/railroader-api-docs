# WaterCylinderController Class

**Namespace:** `Effects`
**Source:** `WaterCylinderController.cs`

## Declaration

```csharp
public class WaterCylinderController : MonoBehaviour
```

## Methods

### PropertyDidChange

```csharp
private void PropertyDidChange(Value value)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `meshRenderer` | `MeshRenderer` | public | - |
| `key` | `string` | public | - |
| `speed` | `float` | public | - |
| `startDelay` | `float` | public | - |
| `stopDelay` | `float` | public | - |
| `sprayEffect` | `VisualEffect` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_material` | `Material` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_isFirstValue` | `bool` | private | - |
| `_currentValue` | `float` | private | - |
| `_targetValue` | `float` | private | - |

