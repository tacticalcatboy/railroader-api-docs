# AutoEngineerConfig Class

**Namespace:** `Model.AI`
**Source:** `AutoEngineerConfig.cs`

## Declaration

```csharp
public class AutoEngineerConfig : ScriptableObject
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `maxVelocityForDistanceLight` | `AnimationCurve` | public | - |
| `maxVelocityForDistanceHeavy` | `AnimationCurve` | public | - |
| `throttlePID` | `PIDController` | public | - |
| `independentPID` | `PIDController` | public | - |
| `trainBrakePID` | `PIDController` | public | - |
| `brakeErrorPower` | `float` | public | - |
| `paddingForSpeedMph` | `AnimationCurve` | public | - |
| `trainBrakeDerivativeGainForNumAirOpenCars` | `AnimationCurve` | public | - |
| `trainBrakeReleaseBelowOutput` | `float` | public | - |
| `crossingWhistlePatterns` | `AnimationCurve[]` | public | - |
| `minimumTimeBetweenCrossingWhistles` | `float` | public | - |
| `applyTimeForNumberOfCars` | `AnimationCurve` | public | - |
| `releaseTimeForNumberOfCars` | `AnimationCurve` | public | - |
| `brakeSetForDeltaVelocityMph` | `AnimationCurve` | public | - |
| `brakeSetMultiplierForVelocityMph` | `AnimationCurve` | public | - |
| `momentumFactor` | `float` | public | - |
| `momentumOffset` | `float` | public | - |
| `momentumRerouteAtCtcSwitch` | `float` | public | - |

