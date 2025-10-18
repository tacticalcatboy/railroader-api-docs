# ExpandedConsole Class

**Namespace:** `UI.Console`
**Source:** `ExpandedConsole.cs`

## Declaration

```csharp
public class ExpandedConsole : MonoBehaviour
```

## Methods

### HistoryUpPerformed

```csharp
private void HistoryUpPerformed(InputAction.CallbackContext obj)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Console` | `IConsoleChildDelegate` | public | - |
| `_canvas` | `Canvas` | private | - |
| `_rect` | `RectTransform` | private | - |
| `_history` | `List<string>` | private | `readonly` |
| `_historyOffset` | `int` | private | - |
| `MaxHistory` | `int` | private | `const` |
| `_lineCount` | `int` | private | - |
| `inputField` | `TMP_InputField` | private | - |
| `textArea` | `TMP_Text` | private | - |
| `scrollRect` | `ScrollRect` | private | - |
| `_window` | `Window` | private | - |
| `_actionHistoryUp` | `InputAction` | private | - |
| `_actionHistoryDown` | `InputAction` | private | - |
| `_scrollCoroutine` | `Coroutine` | private | - |
| `LineCountLimit` | `int` | private | `const` |

