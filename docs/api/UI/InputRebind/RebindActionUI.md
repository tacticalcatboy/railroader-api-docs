# RebindActionUI Class

**Namespace:** `UI.InputRebind`
**Source:** `RebindActionUI.cs`

## Declaration

```csharp
public class RebindActionUI : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `UpdateBindingUIEvent` | `UpdateBindingUIEvent` | public | - |

## Methods

### CheckDuplicateBindings

```csharp
private bool CheckDuplicateBindings(InputAction action, int bindingIndex, bool allCompositeParts)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OnSave` | `Action` | public | - |
| `action` | `InputActionReference` | private | - |
| `bindingId` | `string` | private | - |
| `actionLabel` | `TMP_Text` | private | - |
| `bindingText` | `TMP_Text` | private | - |
| `rebindOverlay` | `GameObject` | private | - |
| `rebindText` | `TMP_Text` | private | - |
| `rebindButton` | `Button` | private | - |
| `resetButton` | `Button` | private | - |
| `updateBindingUIEvent` | `UpdateBindingUIEvent` | private | - |
| `rebindStartEvent` | `InteractiveRebindEvent` | private | - |
| `rebindStopEvent` | `InteractiveRebindEvent` | private | - |
| `_rebindActionUIs` | `List<RebindActionUI>` | private | `static` |
| `_createdInputActionReference` | `InputActionReference` | private | - |
| `_conflict` | `bool` | private | - |

