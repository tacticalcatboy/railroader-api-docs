# CollapsedConsole Class

**Namespace:** `UI.Console`
**Source:** `CollapsedConsole.cs`

## Declaration

```csharp
public sealed class CollapsedConsole : MonoBehaviour, IConsoleChild
```

## Methods

### LayoutLines

```csharp
private void LayoutLines()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `maxVisible` | `int` | public | - |
| `durationVisible` | `float` | public | - |
| `Console` | `IConsoleChildDelegate` | public | - |
| `_removeExpiredCoroutine` | `Coroutine` | private | - |
| `_lines` | `List<ConsoleLine>` | private | `readonly` |

