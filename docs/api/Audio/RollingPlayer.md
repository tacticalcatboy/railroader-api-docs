# RollingPlayer Class

**Namespace:** `Audio`
**Source:** `RollingPlayer.cs`

## Declaration

```csharp
public class RollingPlayer : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Car` | `Car` | private | - |

## Methods

### VolumeForSqueal

```csharp
private float VolumeForSqueal(float curvature, float maxCurvature, float absVelocity, float maxVelocityForCurve, float squeal)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `profile` | `RollingProfile` | public | - |
| `_absVelocity` | `float` | private | - |
| `_rollSources` | `AudioSourcePair` | private | - |
| `_squealSources` | `AudioSourcePair` | private | - |
| `_car` | `Car` | private | - |
| `debugGraph` | `bool` | public | - |
| `_debugGraphSetup` | `bool` | private | - |
| `_coroutineRolling` | `Coroutine` | private | - |
| `_coroutineSqueal` | `Coroutine` | private | - |
| `_movingThreshold` | `float` | private | - |
| `IsMoving` | `bool` | private | - |

