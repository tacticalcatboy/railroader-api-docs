# OpsController Class

**Namespace:** `Model.Ops`
**Source:** `OpsController.cs`

## Declaration

```csharp
public class OpsController : MonoBehaviour, IOpsCarPositionResolver
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `AllIndustryComponents` | `IndustryComponent[]` | private | - |

## Methods

### Sweep

```csharp
public string Sweep(string query)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LastUpdated` | `float` | public | - |
| `Cars` | `List<IOpsCar>` | public | `readonly` |
| `BasePayment` | `int` | public | - |
| `Total` | `int` | public | - |
| `_periodicUpdateCoroutine` | `Coroutine` | private | - |
| `_interchangeSelector` | `InterchangeSelector` | private | - |
| `Areas` | `IEnumerable<Area>` | public | - |
| `EnabledInterchanges` | `IEnumerable<Interchange>` | public | - |
| `TrainController` | `TrainController` | private | `static` |
| `InterchangeShuffle` | `int` | public | `static` |

