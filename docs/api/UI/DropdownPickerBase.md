# DropdownPickerBase Class

**Namespace:** `UI`
**Source:** `DropdownPickerBase.cs`

## Declaration

```csharp
public class DropdownPickerBase : Selectable, IPointerClickHandler, IEventSystemHandler, ISubmitHandler, ICancelHandler
```

## Methods

### DestroyBlocker

```csharp
protected virtual void DestroyBlocker(GameObject blocker)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `dropdown` | `RectTransform` | protected | - |
| `_blocker` | `GameObject` | private | - |
| `_hasSetupTemplate` | `bool` | private | - |
| `HighSortingLayer` | `int` | private | `const` |
| `AlphaFadeSpeed` | `float` | private | `const` |
| `DropdownGameObject` | `GameObject` | private | - |

