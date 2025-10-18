# RiverBuilder Class

**Namespace:** `Helpers`
**Source:** `RiverBuilder.cs`

## Declaration

```csharp
public class RiverBuilder : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `splineProfile` | `SplineProfile` | private | - |
| `_riverPath` | `RiverPath` | private | - |
| `_splines` | `List<RamSpline>` | private | `readonly` |
| `_boundsCenterLocal` | `Vector3` | private | - |
| `_boundsRadius` | `float` | private | - |
| `_generateTask` | `CoroutineTask` | private | - |
| `CullingManager` | `CullingManager` | private | `static` |

