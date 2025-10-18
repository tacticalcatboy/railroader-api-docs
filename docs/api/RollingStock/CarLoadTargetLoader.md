# CarLoadTargetLoader Class

**Namespace:** `RollingStock`
**Source:** `CarLoadTargetLoader.cs`

## Declaration

```csharp
public class CarLoadTargetLoader : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasLoadAvailable` | `bool` | private | - |

## Methods

### SetLoading

```csharp
private void SetLoading(bool loading)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `sourceIndustry` | `Industry` | public | - |
| `load` | `Load` | public | - |
| `outputRate` | `float` | public | - |
| `maximumSpeedInMph` | `float` | public | - |
| `radius` | `float` | public | - |
| `keyValueObject` | `KeyValueObject` | public | - |
| `isLoadingBoolKey` | `string` | public | - |
| `canLoadBoolKey` | `string` | public | - |
| `onlyLoadPlayerCars` | `bool` | public | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_loadCoroutine` | `Coroutine` | private | - |
| `CanLoad` | `bool` | private | - |
| `IsLoading` | `bool` | private | - |

