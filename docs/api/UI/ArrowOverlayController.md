# ArrowOverlayController Class

**Namespace:** `UI`
**Source:** `ArrowOverlayController.cs`

## Declaration

```csharp
public class ArrowOverlayController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `ArrowOverlayController` | public | `static` |

## Methods

### RemoveArrows

```csharp
public void RemoveArrows(IEnumerable<int> keys, bool animated)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `GameObject` | `GameObject` | public | - |
| `MaterialPropertyBlock` | `MaterialPropertyBlock` | public | - |
| `MeshRenderers` | `MeshRenderer[]` | public | - |
| `Key` | `int` | public | - |
| `_shared` | `ArrowOverlayController` | private | `static` |
| `arrowPrefab` | `GameObject` | private | - |
| `_arrowPool` | `Queue<ArrowInstance>` | private | `readonly` |
| `_nextKey` | `int` | private | - |

