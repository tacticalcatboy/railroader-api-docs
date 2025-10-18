# QuickSearchController Class

**Namespace:** `UI.QuickSearch`
**Source:** `QuickSearchController.cs`

## Declaration

```csharp
public class QuickSearchController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `QuickSearchController` | public | `static` |

## Methods

### ScoreQuery

```csharp
private int ScoreQuery(string needle, string haystack)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `canvas` | `Canvas` | private | - |
| `backdropImage` | `Image` | private | - |
| `panelRectTransform` | `RectTransform` | private | - |
| `inputField` | `TMP_InputField` | private | - |
| `inputActions` | `InputActionAsset` | private | - |
| `_actionMap` | `InputActionMap` | private | - |
| `_actionResultNext` | `InputAction` | private | - |
| `_actionResultPrev` | `InputAction` | private | - |
| `_actionActivate` | `InputAction` | private | - |
| `_actionJumpTo` | `InputAction` | private | - |
| `_index` | `int` | private | - |
| `_results` | `List<QuickSearchResult>` | private | - |
| `BindingDisplayStringActivate` | `string` | public | `static` |
| `BindingDisplayStringJumpTo` | `string` | public | `static` |

