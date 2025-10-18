# SteamLocomotiveWheelAnimator Class

**Namespace:** `RollingStock.Steam`
**Source:** `SteamLocomotiveWheelAnimator.cs`

## Declaration

```csharp
public class SteamLocomotiveWheelAnimator : MonoBehaviour, ISteamLocomotiveSubcomponent
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DriverPhase` | `float` | public | - |

## Methods

### CalculateWheelPositionRotation

```csharp
private static void CalculateWheelPositionRotation(SteamLocomotive car, WheelAnimation wheel, SteamLocomotiveDefinition.Wheelset wheelset, out Vector3 targetPosition, out Quaternion targetRotation)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Parameter` | `float` | public | - |
| `InitialPosition` | `Vector3` | public | - |
| `InitialRotation` | `Quaternion` | public | - |
| `InitialPositionLocalToBody` | `Vector3` | public | - |
| `InitialParentRotationLocalToBody` | `Quaternion` | public | - |
| `TargetPosition` | `Vector3` | public | - |
| `TargetRotation` | `Quaternion` | public | - |
| `wheels` | `WheelAnimation[]` | public | - |
| `_playables` | `PlayableHandle[]` | private | - |
| `_locomotive` | `SteamLocomotive` | private | - |
| `_updateWheelTargetsCoroutine` | `Coroutine` | private | - |
| `_wheelAudio` | `WheelAudio` | private | - |

