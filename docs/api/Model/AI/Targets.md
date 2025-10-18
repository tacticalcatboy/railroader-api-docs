# Targets Class

**Namespace:** `Model.AI`
**Source:** `AutoEngineer.cs`

## Declaration

```csharp
public class Targets
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TargetDistance` | `float` | private | - |

## Methods

### TrainBrakeSetToAtLeast

```csharp
private void TrainBrakeSetToAtLeast(float psi)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MaxSpeedMph` | `float` | public | `readonly` |
| `AllTargets` | `List<Target>` | public | `readonly` |
| `AverageGradeUnder` | `float` | public | `readonly` |
| `AverageGradeAhead` | `float` | public | `readonly` |
| `ChangeDirection` | `bool` | public | `readonly` |
| `Mode` | `AutoEngineerMode` | public | `readonly` |
| `NextSignal` | `CTCSignal` | public | `readonly` |
| `_targets` | `Targets` | private | - |
| `_control` | `LocomotiveControlHelper` | private | - |
| `_oiler` | `AutoOiler` | private | - |
| `_graph` | `Graph` | private | - |
| `_loopCoroutine` | `Coroutine` | private | - |
| `_loopKeepalive` | `CoroutineKeepalive` | private | `readonly` |
| `_config` | `AutoEngineerConfig` | private | - |
| `_pendingRunDuration` | `float` | private | - |
| `throttleController` | `PIDController` | private | - |
| `independentController` | `PIDController` | private | - |
| `trainBrakeController` | `PIDController` | private | - |
| `testKeepalive` | `bool` | private | - |
| `BrakeSetThreshold` | `float` | private | `const` |
| `_debugContextualTargetVelocity` | `float` | private | - |
| `_lastState` | `State` | private | - |
| `_cachedCoupled` | `List<Car>` | private | - |
| `_cachedLocomotives` | `List<BaseLocomotive>` | private | - |
| `_cachedAirOpen` | `List<Car>` | private | - |
| `WantsChangeDirection` | `bool` | private | - |
| `WaitForChange` | `IEnumerator` | private | - |
| `LocomotiveVelocityMphAbs` | `float` | private | - |
| `IsStopped` | `bool` | private | - |
| `LogPrefix` | `string` | private | - |
| `WeightParameter` | `float` | private | - |

