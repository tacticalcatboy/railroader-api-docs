# CurveMeshBuilderBase Class

**Namespace:** `BezierCurveMesh`
**Source:** `CurveMeshBuilderBase.cs`

## Declaration

```csharp
public abstract class CurveMeshBuilderBase : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `meshContainer` | `Transform` | protected | - |
| `meshProfile` | `CurveMeshProfile` | protected | - |
| `_renderers` | `Renderer[]` | private | - |
| `_boundsCenterLocal` | `Vector3` | private | - |
| `_boundsRadius` | `float` | private | - |

