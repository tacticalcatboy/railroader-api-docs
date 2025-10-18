# TutorialManager Class

**Namespace:** `UI.Tutorial`
**Source:** `TutorialManager.cs`

## Declaration

```csharp
public class TutorialManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `TutorialManager` | public | `static` |

## Methods

### OnDestroy

```csharp
private void OnDestroy()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ObjectId` | `string` | private | `const` |
| `KeyClosed` | `string` | private | `const` |
| `KeyComplete` | `string` | private | `const` |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_window` | `InteractiveBookWindow` | private | - |
| `_shared` | `TutorialManager` | private | `static` |
| `Complete` | `bool` | public | - |

