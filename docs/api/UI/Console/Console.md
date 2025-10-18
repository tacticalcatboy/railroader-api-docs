# Console Class

**Namespace:** `UI.Console`
**Source:** `Console.cs`

## Declaration

```csharp
public class Console : MonoBehaviour, IConsoleChildDelegate
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `shared` | `Console` | public | `static` |

## Methods

### CreateLine

```csharp
public TMP_Text CreateLine(string text, Transform parent)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `window` | `Window` | private | - |
| `expanded` | `ExpandedConsole` | private | - |
| `inputActions` | `InputActionAsset` | private | - |
| `_collapsed` | `CollapsedConsole` | private | - |
| `_pool` | `ConsoleLinePool` | private | - |
| `_isCollapsing` | `bool` | private | - |
| `_lastCollapsed` | `float` | private | - |
| `_consoleActionMap` | `InputActionMap` | private | - |

