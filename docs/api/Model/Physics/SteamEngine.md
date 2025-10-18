# SteamEngine Class

**Namespace:** `Model.Physics`
**Source:** `SteamEngine.cs`

## Declaration

```csharp
public class SteamEngine : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CoalConsumptionRate` | `float` | public | - |

## Methods

### CalculateTractiveEffort

```csharp
public float CalculateTractiveEffort(float wheelVelocityMph)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `numberOfCylinders` | `int` | public | - |
| `pistonDiameterInches` | `float` | public | - |
| `pistonStrokeInches` | `float` | public | - |
| `maximumBoilerPressure` | `float` | public | - |
| `driverDiameterInches` | `float` | public | - |
| `weightOnDrivers` | `float` | public | - |
| `totalHeatingSurface` | `float` | public | - |
| `reverser` | `float` | public | - |
| `regulator` | `float` | public | - |
| `running` | `bool` | public | - |
| `tractiveEffort` | `float` | public | - |
| `pressure` | `float` | public | - |
| `MaximumSpeedMph` | `float` | public | - |
| `_reverserPowerMultiplier` | `float` | private | - |
| `_estimatedGrateSqFt` | `float` | private | - |
| `NormalizedTractiveEffort` | `float` | public | - |

