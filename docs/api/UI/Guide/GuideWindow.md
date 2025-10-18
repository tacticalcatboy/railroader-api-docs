# GuideWindow Class

**Namespace:** `UI.Guide`
**Source:** `GuideWindow.cs`

## Declaration

```csharp
public class GuideWindow : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Title` | `string` | public | - |

## Methods

### ScrollToPosition

```csharp
private static IEnumerator ScrollToPosition(RectTransform rectTransform, string linkId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LinkAnchors` | `HashSet<string>` | public | - |
| `Name` | `string` | public | - |
| `Path` | `string` | public | - |
| `Sections` | `List<Section>` | public | - |
| `_window` | `Window` | private | - |
| `_instance` | `GuideWindow` | private | `static` |
| `_selectedItem` | `UIState<string>` | private | `readonly` |
| `_panel` | `UIPanel` | private | - |
| `_contents` | `List<Document>` | private | - |
| `Instance` | `GuideWindow` | private | `static` |

