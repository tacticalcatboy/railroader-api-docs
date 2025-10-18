# MapDrag Class

**Namespace:** `UI.Map`
**Source:** `MapDrag.cs`

## Declaration

```csharp
public class MapDrag : MonoBehaviour, IPointerDownHandler, IEventSystemHandler, IDragHandler, IPointerEnterHandler, IPointerExitHandler, IPointerClickHandler
```

## Methods

### OnPointerEnter

```csharp
public void OnPointerEnter(PointerEventData eventData)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OnDragStart` | `Action` | public | - |
| `OnDragChange` | `Action<Vector2>` | public | - |
| `OnTeleport` | `Action<Vector2>` | public | - |
| `OnClick` | `Action<Vector2>` | public | - |
| `_rectTransform` | `RectTransform` | private | - |
| `_window` | `Window` | private | - |
| `_downPointerPosition` | `Vector2` | private | - |
| `_currentPointerPosition` | `Vector2` | private | - |
| `_pointerOver` | `bool` | private | - |
| `_isDragging` | `bool` | private | - |
| `RectHeight` | `float` | public | - |

