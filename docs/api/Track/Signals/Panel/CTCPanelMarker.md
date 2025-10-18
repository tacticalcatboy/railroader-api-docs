# CTCPanelMarker Class

**Namespace:** `Track.Signals.Panel`
**Source:** `CTCPanelMarker.cs`

## Declaration

```csharp
public class CTCPanelMarker : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CanvasSize` | `Vector2` | private | - |

## Methods

### InferColorFromText

```csharp
private static Color InferColorFromText(string text)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `manager` | `CTCPanelMarkerManager` | public | - |
| `label` | `TMP_Text` | private | - |
| `image` | `Image` | private | - |
| `_dragCoroutine` | `Coroutine` | private | - |
| `_canvasRectTransform` | `RectTransform` | private | - |
| `_pointAtActivate` | `Vector2` | private | - |
| `_camera` | `Camera` | private | - |
| `_rectTransform` | `RectTransform` | private | - |
| `_anchoredPositionAtActivate` | `Vector2` | private | - |
| `_lastDeactivate` | `float` | private | - |
| `_currentFace` | `CTCPanelSchematicFace` | private | - |
| `_id` | `string` | private | - |
| `_lastSentPosition` | `Vector2` | private | - |
| `_targetAnchoredPosition` | `Vector2` | private | - |
| `_animateToTarget` | `Coroutine` | private | - |
| `InsetBoundsWidth` | `float` | private | `const` |
| `InsetBoundsHeight` | `float` | private | `const` |
| `CharacterLimit` | `int` | private | `const` |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

