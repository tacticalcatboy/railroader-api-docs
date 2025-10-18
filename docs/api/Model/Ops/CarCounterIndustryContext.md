# CarCounterIndustryContext Class

**Namespace:** `Model.Ops`
**Source:** `CarCounterIndustryContext.cs`

## Declaration

```csharp
public class CarCounterIndustryContext : IIndustryContext
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DeltaTime` | `float` | public | - |

## Methods

### RemoveCar

```csharp
public void RemoveCar(IOpsCar car)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Cars` | `HashSet<MockCar>` | public | - |
| `OrderedAway` | `HashSet<MockCar>` | public | `readonly` |
| `Now` | `GameDateTime` | public | - |
| `PortionOfDayUntilNextRegularService` | `float` | public | - |

