# TurntableController Class

**Namespace:** `Track`
**Source:** `TurntableController.cs`

## Declaration

```csharp
public class TurntableController : MonoBehaviour, IMoverController
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TargetSpeedPercent` | `float` | private | - |

## Methods

### CanContinueMoving

```csharp
private bool CanContinueMoving()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `bridgeTransform` | `Transform` | private | - |
| `controlLever` | `ContinuousControl` | private | - |
| `_speed` | `float` | private | - |
| `_wasMoving` | `bool` | private | - |
| `_propertyObject` | `KeyValueObject` | private | - |
| `_controlLeverObserver` | `IDisposable` | private | - |
| `_goalPositionOffset` | `Vector3` | private | - |
| `_goalRotation` | `Quaternion` | private | - |
| `_warnedCarId` | `string` | private | - |

