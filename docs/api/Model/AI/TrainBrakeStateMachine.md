# TrainBrakeStateMachine Class

**Namespace:** `Model.AI`
**Source:** `TrainBrakeStateMachine.cs`

## Declaration

```csharp
public class TrainBrakeStateMachine
```

## Methods

### Reset

```csharp
public void Reset()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ApplyTimeForNumberOfCars` | `AnimationCurve` | internal | - |
| `ReleaseTimeForNumberOfCars` | `AnimationCurve` | internal | - |
| `BrakeSetForDeltaVelocityMph` | `AnimationCurve` | internal | - |
| `BrakeSetMultiplierForVelocityMph` | `AnimationCurve` | internal | - |
| `NumberOfCars` | `int` | public | - |
| `ApplyTimeout` | `float` | public | - |
| `ReleaseTimeout` | `float` | public | - |
| `VelocityAfterApply` | `float` | internal | - |
| `VelocityAfterRelease` | `float` | internal | - |
| `ApplyVelocityThreshold` | `float` | internal | - |
| `ReleaseVelocityThreshold` | `float` | internal | - |

