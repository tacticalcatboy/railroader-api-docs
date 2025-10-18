# StationAgent Class

**Namespace:** `Model`
**Source:** `StationAgent.cs`

## Declaration

```csharp
public class StationAgent : MonoBehaviour, IPickable
```

## Methods

### CacheUpdateCoroutine

```csharp
private IEnumerator CacheUpdateCoroutine()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `area` | `Area` | private | - |
| `secondaryAreas` | `List<Area>` | private | - |
| `passengerStop` | `PassengerStop` | private | - |
| `_freightCarList` | `OpsCarList` | private | `readonly` |
| `_cacheUpdateCoroutine` | `Coroutine` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

