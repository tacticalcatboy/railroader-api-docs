# CarLoaderSequencer Class

**Namespace:** `RollingStock`
**Source:** `CarLoaderSequencer.cs`

## Declaration

```csharp
public class CarLoaderSequencer : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `AnimateLoad` | `bool` | private | - |

## Methods

### LogState

```csharp
private void LogState(string message)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `keyValueObject` | `KeyValueObject` | public | - |
| `readWantsLoadingKey` | `string` | public | - |
| `readIsLoadingKey` | `string` | public | - |
| `writeCanLoadKey` | `string` | public | - |
| `writePrepareLoadKey` | `string` | public | - |
| `writeAnimateLoadKey` | `string` | public | - |
| `prepareLoadingDelay` | `float` | public | - |
| `startLoadingDelay` | `float` | public | - |
| `stopLoadingDelay` | `float` | public | - |
| `cleanupLoadingDelay` | `float` | public | - |
| `logStateChanges` | `bool` | public | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_loopCoroutine` | `Coroutine` | private | - |
| `WantsLoading` | `bool` | private | - |
| `IsLoading` | `bool` | private | - |

