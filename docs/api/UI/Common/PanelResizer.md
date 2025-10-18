# PanelResizer Class

**Namespace:** `UI.Common`
**Source:** `PanelResizer.cs`

## Declaration

```csharp
public class PanelResizer : MonoBehaviour, IPointerDownHandler, IEventSystemHandler, IDragHandler, IPointerUpHandler
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasUserResized` | `bool` | public | - |

## Methods

### OnDrag

```csharp
public void OnDrag(PointerEventData data)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `minSize` | `Vector2` | public | - |
| `maxSize` | `Vector2` | public | - |
| `_initialSizeDelta` | `Vector2` | private | - |
| `_currentPointerPosition` | `Vector2` | private | - |
| `_initialPointerPosition` | `Vector2` | private | - |
| `_window` | `Window` | private | - |
| `_windowRectTransform` | `RectTransform` | private | - |

