# CarLoadAnimator Class

**Namespace:** `RollingStock.Controls`
**Source:** `CarLoadAnimator.cs`

## Declaration

```csharp
public class CarLoadAnimator : MonoBehaviour
```

## Methods

### TargetTime

```csharp
private float TargetTime()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `slot` | `int` | public | - |
| `loadIdentifiers` | `List<string>` | public | - |
| `carLoadGameObject` | `GameObject` | public | - |
| `animator` | `Animator` | public | - |
| `animationClip` | `AnimationClip` | public | - |
| `clipStartsFull` | `bool` | public | - |
| `_clipPlayable` | `PlayableHandle` | private | - |
| `_isInitial` | `bool` | private | - |
| `_updateCoroutine` | `Coroutine` | private | - |
| `_observer` | `IDisposable` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_car` | `Car` | private | - |
| `LoadKey` | `string` | private | - |

