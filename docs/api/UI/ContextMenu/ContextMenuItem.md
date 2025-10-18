# ContextMenuItem Class

**Namespace:** `UI.ContextMenu`
**Source:** `ContextMenuItem.cs`

## Declaration

```csharp
public class ContextMenuItem : MonoBehaviour, IPointerEnterHandler, IEventSystemHandler, IPointerExitHandler, IPointerClickHandler
```

## Methods

### OnPointerExit

```csharp
public void OnPointerExit(PointerEventData eventData)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `image` | `Image` | public | - |
| `label` | `TMP_Text` | public | - |
| `canvasGroup` | `CanvasGroup` | public | - |
| `wedgeImage` | `WedgeImage` | public | - |
| `textContainer` | `RectTransform` | public | - |
| `colorDefault` | `Color` | public | - |
| `colorHover` | `Color` | public | - |
| `OnClick` | `Action` | public | - |
| `_defaultFontSize` | `float` | private | - |

