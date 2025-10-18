# RestoreNotifier Class

**Namespace:** `Game.State`
**Source:** `RestoreNotifier.cs`

## Declaration

```csharp
public class RestoreNotifier : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `RestoreNotifier` | public | `static` |

## Methods

### NotifyPending

```csharp
private void NotifyPending()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Priority` | `int` | public | `readonly` |
| `Observer` | `object` | public | `readonly` |
| `Action` | `Action` | public | `readonly` |
| `_state` | `State` | private | - |
| `_pending` | `List<Entry>` | private | `readonly` |

