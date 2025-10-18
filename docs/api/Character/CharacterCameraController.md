# CharacterCameraController Class

**Namespace:** `Character`
**Source:** `CharacterCameraController.cs`

## Declaration

```csharp
public class CharacterCameraController : MonoBehaviour
```

## Methods

### SetRotation

```csharp
public void SetRotation(Quaternion rotation)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `defaultVerticalAngle` | `float` | public | - |
| `minVerticalAngle` | `float` | public | - |
| `maxVerticalAngle` | `float` | public | - |
| `rotationSpeed` | `float` | public | - |
| `rotationSharpness` | `float` | public | - |
| `_transform` | `Transform` | private | - |
| `_distanceIsObstructed` | `bool` | private | - |
| `_targetPitch` | `float` | private | - |
| `_targetYaw` | `float` | private | - |
| `_lastLean` | `Lean` | private | - |
| `_camera` | `Camera` | private | - |
| `_targetFieldOfView` | `float` | private | - |
| `DefaultFOV` | `float` | private | `static` |
| `DefaultWideFOV` | `float` | private | `static` |

