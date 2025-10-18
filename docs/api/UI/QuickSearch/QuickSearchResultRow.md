# QuickSearchResultRow Class

**Namespace:** `UI.QuickSearch`
**Source:** `QuickSearchResultRow.cs`

## Declaration

```csharp
public class QuickSearchResultRow : MonoBehaviour, ILazyScrollListCell
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ListIndex` | `int` | public | - |

## Methods

### Configure

```csharp
public void Configure(int listIndex, object data)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `highlightedImage` | `Image` | private | - |
| `label` | `TMP_Text` | private | - |
| `smallLabel` | `TMP_Text` | private | - |
| `Actions` | `QuickSearchAction[]` | private | `static` |
| `RectTransform` | `RectTransform` | public | - |

