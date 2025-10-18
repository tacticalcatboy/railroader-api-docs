# SemaphoreHeadController Class

**Namespace:** `Track`
**Source:** `SemaphoreHeadController.cs`

## Declaration

```csharp
public class SemaphoreHeadController : MonoBehaviour
```

## Methods

### SetAspectCoroutine

```csharp
private IEnumerator SetAspectCoroutine(Aspect aspect)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `semaphoreArmAnimationClip` | `AnimationClip` | public | - |
| `animator` | `Animator` | public | - |
| `lampMeshRenderer` | `MeshRenderer` | public | - |
| `lampMaterialIndex` | `int` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_playable` | `PlayableHandle` | private | - |
| `_clipPlayablePort` | `int` | private | - |
| `raiseSpeed` | `float` | public | - |
| `fallSpeed` | `float` | public | - |
| `_lastColor` | `Color` | private | - |
| `_lastParam` | `float` | private | - |
| `_setAspectCoroutine` | `Coroutine` | private | - |

