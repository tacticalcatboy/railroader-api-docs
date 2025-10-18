# CarAirSystem Class

**Namespace:** `Model.Physics`
**Source:** `CarAirSystem.cs`

## Declaration

```csharp
public class CarAirSystem : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DefersToLocomotiveAir` | `bool` | public | - |

## Methods

### UpdateBrakeLineIndividualA

```csharp
private void UpdateBrakeLineIndividualA(float dt)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BrakeLine` | `Reservoir` | public | `readonly` |
| `BrakeReservoir` | `Reservoir` | public | `readonly` |
| `BrakeCylinder` | `Reservoir` | public | `readonly` |
| `BrakeLineToReservoir` | `AirConnection` | public | `readonly` |
| `ReservoirToCylinder` | `AirConnection` | public | `readonly` |
| `CylinderToOutside` | `AirConnection` | private | `readonly` |
| `BrakeLineConnectionA` | `AirConnection` | private | `readonly` |
| `BrakeLineConnectionB` | `AirConnection` | private | `readonly` |
| `TenderMainResToBrakeCylinder` | `VentedValve` | private | `readonly` |
| `TenderMainResToMainRes` | `VentedValve` | private | `readonly` |
| `brakePercent` | `float` | public | - |
| `handbrakeApplied` | `bool` | public | - |
| `exhaustFlow` | `float` | public | - |
| `airFlow` | `float` | private | - |
| `anglecockFlowA` | `float` | public | - |
| `anglecockFlowB` | `float` | public | - |
| `car` | `Car` | public | - |
| `NeedsSend` | `bool` | public | - |
| `LastSentTick` | `long` | public | - |
| `AnglecockClosedThreshold` | `float` | public | `const` |
| `anglecockA` | `float` | private | - |
| `anglecockB` | `float` | private | - |

