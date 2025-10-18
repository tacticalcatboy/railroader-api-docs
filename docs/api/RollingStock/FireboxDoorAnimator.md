# FireboxDoorAnimator Class

**Namespace:** `RollingStock`
**Source:** `FireboxDoorAnimator.cs`

## Declaration

```csharp
public class FireboxDoorAnimator : MonoBehaviour
```

## Methods

### PropertyDidChange

```csharp
private void PropertyDidChange(Value value)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `key` | `string` | public | - |
| `animationClip` | `AnimationClip` | public | - |
| `animationSpeed` | `float` | public | - |
| `animator` | `Animator` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_playable` | `PlayableHandle` | private | - |
| `_targetTime` | `float` | private | - |
| `_updateCoroutine` | `Coroutine` | private | - |

