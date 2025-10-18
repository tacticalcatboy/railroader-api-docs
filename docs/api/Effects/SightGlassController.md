# SightGlassController Class

**Namespace:** `Effects`
**Source:** `SightGlassController.cs`

## Declaration

```csharp
public class SightGlassController : MonoBehaviour
```

## Methods

### LoadValueDidChange

```csharp
private void LoadValueDidChange(float level)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `waterRenderer` | `MeshRenderer` | private | - |
| `targetForce` | `float` | public | - |
| `springStiffness` | `float` | public | - |
| `springDamping` | `float` | public | - |
| `springMass` | `float` | public | - |
| `_waterCar` | `Car` | private | - |
| `_fuelObserver` | `IDisposable` | private | - |
| `_targetLevel` | `float` | private | - |
| `_lastSetLevel` | `float` | private | - |
| `_hasSetMaterial` | `bool` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_material` | `Material` | private | - |
| `_velocity` | `float` | private | - |

