# CarMover Class

**Namespace:** `Model`
**Source:** `CarMover.cs`

## Declaration

```csharp
public class CarMover : IMoverController
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DebugId` | `string` | public | - |

## Methods

### CheckToAwakenMover

```csharp
private void CheckToAwakenMover(float distanceMoved)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_physicsMover` | `PhysicsMover` | private | - |
| `_rigidbody` | `Rigidbody` | private | - |
| `_moverPosition` | `Vector3` | private | - |
| `_moverRotation` | `Quaternion` | private | - |
| `_velocity` | `Vector3` | private | - |
| `_timeLastMoved` | `float` | private | - |
| `_physicsMoverEnabled` | `bool` | private | - |
| `_playerNearby` | `bool` | private | - |
| `_movedRecently` | `bool` | private | - |
| `_bodyTransform` | `Transform` | private | - |
| `Position` | `Vector3` | public | - |
| `Rotation` | `Quaternion` | public | - |
| `RigidbodyMoverPosition` | `Vector3` | private | - |

