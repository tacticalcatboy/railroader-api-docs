# LazyScrollList Class

**Namespace:** `UI.LazyScrollList`
**Source:** `LazyScrollList.cs`

## Declaration

```csharp
public class LazyScrollList : MonoBehaviour
```

## Methods

### GetStartEndIndexFloat

```csharp
private void GetStartEndIndexFloat(out float startIndex, out float endIndex)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `cellPrefab` | `GameObject` | public | - |
| `_data` | `List<object>` | private | - |
| `_visibleCells` | `List<ILazyScrollListCell>` | private | `readonly` |
| `_cellPool` | `CellPool<ILazyScrollListCell>` | private | - |
| `_cellHeight` | `float` | private | - |
| `_scrollRect` | `ScrollRect` | private | - |
| `_scrollRectTransform` | `RectTransform` | private | - |
| `_lastNormalizedY` | `float` | private | - |
| `_lastScrollRectContentWidth` | `float` | private | - |
| `VisibleCells` | `IReadOnlyCollection<ILazyScrollListCell>` | public | - |

