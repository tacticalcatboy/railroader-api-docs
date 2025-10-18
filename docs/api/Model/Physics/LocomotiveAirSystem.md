# LocomotiveAirSystem Class

**Namespace:** `Model.Physics`
**Source:** `LocomotiveAirSystem.cs`

## Declaration

```csharp
public class LocomotiveAirSystem : CarAirSystem
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasFuel` | `bool` | public | - |

## Methods

### _ShouldDeferToLocomotiveAir

```csharp
private bool _ShouldDeferToLocomotiveAir(out LocomotiveAirSystem locomotiveAirSystem)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MainReservoir` | `Reservoir` | public | `readonly` |
| `trainBrakePressure` | `float` | public | - |
| `locomotiveBrakePressure` | `float` | public | - |
| `_mainReservoirToBrakeLine` | `VentedValve` | private | `readonly` |
| `_mainReservoirToBrakeCylinder` | `VentedValve` | private | `readonly` |
| `maximumLocomotiveBrakePressure` | `float` | public | - |
| `brakeFeedValvePressure` | `float` | public | - |
| `compressorLimitLower` | `float` | public | - |
| `compressorLimitUpper` | `float` | public | - |
| `compressorRunning` | `bool` | public | - |
| `compressorRate` | `float` | public | - |
| `brakeFeedValveFlow` | `float` | public | - |
| `_lapTrainBrakePressure` | `float` | private | - |
| `_locomotiveBrakeLineMemory` | `float` | private | - |
| `_locomotiveBrakeLineBank` | `float` | private | - |
| `IsCutOut` | `bool` | public | - |

