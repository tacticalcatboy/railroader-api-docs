# NoticeRow Class

**Namespace:** `Game.Notices`
**Source:** `NoticeRow.cs`

## Declaration

```csharp
public class NoticeRow : MonoBehaviour, IPointerEnterHandler, IEventSystemHandler, IPointerExitHandler
```

## Methods

### SetOffscreen

```csharp
public void SetOffscreen(bool offscreen, bool animated)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `label` | `TMP_Text` | public | - |
| `dismissButtonGroup` | `CanvasGroup` | public | - |
| `contentRectTransform` | `RectTransform` | public | - |
| `OnDismiss` | `Action` | public | - |

