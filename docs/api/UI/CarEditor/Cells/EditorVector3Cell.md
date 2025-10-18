# EditorVector3Cell Class

**Namespace:** `UI.CarEditor.Cells`
**Source:** `EditorVector3Cell.cs`

## Declaration

```csharp
public class EditorVector3Cell : EditorCellBase
```

## Methods

### Configure

```csharp
public void Configure(string labelText, Vector2 vector, Action<Vector2> didSet)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_value` | `Vector3` | private | - |
| `inputFieldX` | `TMP_InputField` | private | - |
| `inputFieldY` | `TMP_InputField` | private | - |
| `inputFieldZ` | `TMP_InputField` | private | - |
| `sliderAreaX` | `SliderArea` | private | - |
| `sliderAreaY` | `SliderArea` | private | - |
| `sliderAreaZ` | `SliderArea` | private | - |
| `_action` | `Action<Vector3>` | private | - |

