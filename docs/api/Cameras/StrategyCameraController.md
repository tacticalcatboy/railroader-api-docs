# StrategyCameraController Class

**Namespace:** `Cameras`
**Source:** `StrategyCameraController.cs`

## Declaration

```csharp
public class StrategyCameraController : MonoBehaviour, ICameraSelectable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `FollowCar` | `Car` | public | - |

## Methods

### SnapToGround

```csharp
private Vector3 SnapToGround(Vector3 position, bool immediate = false)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `normalSpeed` | `float` | public | - |
| `fastSpeed` | `float` | public | - |
| `fasterSpeed` | `float` | public | - |
| `zoomSpeed` | `float` | public | - |
| `targetHeightFollow` | `float` | public | - |
| `targetHeightFree` | `float` | public | - |
| `distanceToSpeed` | `AnimationCurve` | public | - |
| `zoomMultiplier` | `AnimationCurve` | public | - |
| `zoomAngleSpeed` | `float` | private | - |
| `zoomAngleYSpeed` | `float` | private | - |
| `_distance` | `float` | private | - |
| `_angleX` | `float` | private | - |
| `_extraHeightForGround` | `float` | private | - |
| `_angleY` | `float` | private | - |
| `_movementVelocity` | `Vector3` | private | - |
| `_distanceVelocity` | `float` | private | - |
| `_angleXVelocity` | `float` | private | - |
| `_angleYVelocity` | `float` | private | - |
| `_targetHeight` | `float` | private | - |
| `_rigidbody` | `Rigidbody` | private | - |
| `_targetPosition` | `Vector3` | private | - |
| `_moveTimer` | `float` | private | - |
| `_panStartTarget` | `Vector3` | private | - |
| `_panStartCameraPosition` | `Vector3` | private | - |
| `_panPlane` | `Plane` | private | - |
| `_rotateStarted` | `bool` | private | - |
| `_rotateStartPosition` | `Vector3` | private | - |
| `_rotateCurrentPosition` | `Vector3` | private | - |
| `_mainCamera` | `Camera` | private | - |
| `_followCar` | `Car` | private | - |
| `_followCarInitialRotation` | `Quaternion` | private | - |
| `_extraRotationY` | `float` | private | - |
| `_lateFixedUpdate` | `Coroutine` | private | - |
| `_movementInput` | `Vector3` | private | - |
| `_distanceInput` | `float` | private | - |
| `_angleXInput` | `float` | private | - |
| `_angleYInput` | `float` | private | - |
| `snapToGroundResponsiveness` | `float` | private | - |
| `_targetSnapPosition` | `Vector3` | private | - |
| `PanMouseButton` | `int` | private | `const` |
| `CameraContainer` | `Transform` | public | - |
| `GroundPosition` | `Vector3` | public | - |
| `ZoomDelta` | `float` | private | - |

