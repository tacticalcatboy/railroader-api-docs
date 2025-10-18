# Frame Struct

**Namespace:** `Avatar`
**Source:** `RemoteAvatar.cs`

## Declaration

```csharp
private struct Frame
```

## Methods

### ApplyToAvatar

```csharp
private void ApplyToAvatar(Vector3 position, Quaternion rotation, Quaternion look, Vector3 velocity, Vector3 animationVelocity, AvatarPose pose)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Tick` | `long` | public | `readonly` |
| `Position` | `Vector3` | public | `readonly` |
| `Forward` | `Vector3` | public | `readonly` |
| `Look` | `Vector3` | public | `readonly` |
| `Velocity` | `Vector3` | public | `readonly` |
| `RelativeToCarId` | `string` | public | `readonly` |
| `Pose` | `AvatarPose` | public | `readonly` |
| `avatar` | `AvatarPrefab` | public | - |
| `Delay` | `long` | private | `const` |
| `_frames` | `CircularBuffer<Frame>` | private | `readonly` |
| `Animator` | `AvatarAnimator` | private | - |
| `Rigidbody` | `Rigidbody` | private | - |
| `DisplayTick` | `long` | private | `static` |

