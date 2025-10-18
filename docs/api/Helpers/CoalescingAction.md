# CoalescingAction Class

**Namespace:** `Helpers`
**Source:** `CoalescingAction.cs`

## Declaration

```csharp
public class CoalescingAction : IDisposable
```

## Methods

### Loop

```csharp
private IEnumerator Loop()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_readyToWork` | `Func<bool>` | private | `readonly` |
| `_work` | `Action` | private | `readonly` |
| `_component` | `MonoBehaviour` | private | `readonly` |
| `_coroutine` | `Coroutine` | private | - |

