# RendererCuller Class

**Namespace:** `Helpers.Culling`
**Source:** `RendererCuller.cs`

## Declaration

```csharp
public class RendererCuller : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### ResetCulling

```csharp
private void ResetCulling()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_cullingState` | `CullingState` | private | - |
| `_cullRenderers` | `Renderer[]` | private | - |
| `cullingManagerName` | `CullingManagerName` | private | - |
| `visibleDistanceBand` | `int` | public | - |
| `radius` | `float` | public | - |

