# AutoOiler Class

**Namespace:** `Model.AI`
**Source:** `AutoOiler.cs`

## Declaration

```csharp
public class AutoOiler : MonoBehaviour
```

## Methods

### PayWages

```csharp
private void PayWages()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_coroutine` | `Coroutine` | private | - |
| `_cars` | `IReadOnlyList<Car>` | private | - |
| `_reverse` | `bool` | private | - |
| `_originCar` | `Car` | private | - |
| `_pendingRunDuration` | `float` | private | - |
| `_oiledCount` | `int` | private | - |
| `StartDelay` | `float` | private | `const` |
| `TimeToFullyOil` | `float` | private | `const` |
| `TimeToWalkCar` | `float` | private | `const` |
| `OilIfBelow` | `float` | private | `const` |

