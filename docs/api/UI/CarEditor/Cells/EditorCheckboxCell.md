# EditorCheckboxCell Class

**Namespace:** `UI.CarEditor.Cells`
**Source:** `EditorCheckboxCell.cs`

## Declaration

```csharp
public class EditorCheckboxCell : EditorCellBase
```

## Methods

### Configure

```csharp
public void Configure(string labelText, bool value, Action<bool> didSet)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `toggle` | `Toggle` | private | - |
| `_action` | `Action<bool>` | private | - |
| `_value` | `bool` | private | - |

