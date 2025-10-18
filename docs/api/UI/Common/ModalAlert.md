# ModalAlert Class

**Namespace:** `UI.Common`
**Source:** `ModalAlert.cs`

## Declaration

```csharp
public class ModalAlert : MonoBehaviour
```

## Methods

### Configure

```csharp
public void Configure(Action<UIPanelBuilder, Action> builderDismissClosure, int width)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `canvasGroup` | `CanvasGroup` | private | - |
| `alertRectTransform` | `RectTransform` | private | - |
| `contentRectTransform` | `RectTransform` | private | - |
| `builderAssets` | `UIBuilderAssets` | private | - |
| `_actionSelected` | `bool` | private | - |
| `_panel` | `UIPanel` | private | - |

