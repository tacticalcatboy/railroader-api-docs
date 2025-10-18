# Chuff Class

**Namespace:** `RollingStock`
**Source:** `Chuff.cs`

## Declaration

```csharp
public class Chuff : MonoBehaviour, IChuffProvider, ISteamLocomotiveSubcomponent, CullingManager.ICullingEventHandler
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Delegate` | `IDynamicChuffDelegate` | public | - |

## Methods

### ApplyDistanceMoved

```csharp
public void ApplyDistanceMoved(MovementInfo info, float driverVelocity, float absReverser, float absThrottle, float driverPhase)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `profile` | `ChuffProfile` | private | - |
| `chuffFilter` | `ChuffFilter` | private | - |
| `_driverCircumference` | `float` | private | - |
| `_movedLastFixedUpdate` | `bool` | private | - |
| `_absVelocity` | `float` | private | - |
| `_tractiveEffort` | `float` | private | - |
| `_tractiveEffortReported` | `float` | private | - |
| `_absThrottle` | `float` | private | - |
| `throttleResponsiveness` | `float` | private | - |

