# PlayerController Class

**Namespace:** `Character`
**Source:** `PlayerController.cs`

## Declaration

```csharp
public class PlayerController : MonoBehaviour, ICameraSelectable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsOnGround` | `bool` | public | - |

## Methods

### TryFixPlayerPosition

```csharp
private bool TryFixPlayerPosition(Vector3 characterPosition, Vector3 potentialPosition)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `character` | `CharacterController` | public | - |
| `cameraController` | `CharacterCameraController` | public | - |
| `_leanDownAt` | `float` | private | - |
| `_leanLastActive` | `Lean` | private | - |
| `_mouseLookInput` | `MouseLookInput` | private | - |
| `_characterInputs` | `PlayerCharacterInputs` | private | - |
| `_attachedCarId` | `string` | private | - |
| `_attachedCarLoadToken` | `IDisposable` | private | - |
| `_carCheckerCoroutine` | `Coroutine` | private | - |
| `cameraContainer` | `Transform` | private | - |
| `_isSelected` | `bool` | private | - |
| `_transmitter` | `CharacterPositionTransmitter` | private | - |
| `CameraContainer` | `Transform` | public | - |
| `GroundPosition` | `Vector3` | public | - |

