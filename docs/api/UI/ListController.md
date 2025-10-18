# ListController Class

**Namespace:** `UI`
**Source:** `ListController.cs`

## Declaration

```csharp
public class ListController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Value` | `object` | public | - |

## Methods

### SetSelected

```csharp
private void SetSelected(string selectedId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Identifier` | `string` | public | `readonly` |
| `sectionRowTemplate` | `ListRow` | private | - |
| `itemRowTemplate` | `ListRow` | private | - |
| `scrollContent` | `RectTransform` | private | - |
| `scrollRect` | `ScrollRect` | private | - |
| `OnSelectItem` | `Action<string>` | public | - |
| `_selectedId` | `string` | private | - |

