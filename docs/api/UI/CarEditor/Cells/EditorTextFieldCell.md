# EditorTextFieldCell Class

**Namespace:** `UI.CarEditor.Cells`
**Source:** `EditorTextFieldCell.cs`

## Declaration

```csharp
public class EditorTextFieldCell : EditorCellBase
```

## Methods

### Configure

```csharp
public void Configure(string labelText, int value, bool editable, Action<int> didSet)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `inputField` | `TMP_InputField` | private | - |
| `_action` | `Action<string>` | private | - |
| `_value` | `string` | private | - |

