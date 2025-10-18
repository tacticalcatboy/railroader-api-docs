# LocationIndicatorHoverArea Class

**Namespace:** `UI`
**Source:** `LocationIndicatorHoverArea.cs`

## Declaration

```csharp
public class LocationIndicatorHoverArea : MonoBehaviour, IPointerEnterHandler, IEventSystemHandler, IPointerExitHandler, IPointerClickHandler
```

## Methods

### OnPointerExit

```csharp
public void OnPointerExit(PointerEventData eventData)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_controller` | `LocationIndicatorController` | private | - |
| `spanIds` | `List<string>` | public | `readonly` |
| `_addedTokens` | `List<string>` | private | `readonly` |
| `_segmentTokens` | `List<string>` | private | `readonly` |

