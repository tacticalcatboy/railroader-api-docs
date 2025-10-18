# CharacterPositionTransmitter Class

**Namespace:** `Character`
**Source:** `CharacterPositionTransmitter.cs`

## Declaration

```csharp
public class CharacterPositionTransmitter : MonoBehaviour
```

## Methods

### SendIfNeeded

```csharp
private void SendIfNeeded(Vector3 position, Vector3 forward, Vector3 look, Vector3 velocity, AvatarPose pose, string relativeToCarId, bool force)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_firstPersonController` | `PlayerController` | private | - |
| `_lastSentUpdateCharacterPosition` | `UpdateCharacterPosition` | private | - |
| `_lastSentTick` | `long` | private | - |

