# WheelAudio Class

**Namespace:** `RollingStock`
**Source:** `WheelAudio.cs`

## Declaration

```csharp
public class WheelAudio : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ShouldRunLoop` | `bool` | private | - |

## Methods

### RollClack

```csharp
private void RollClack(float distance)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_profile` | `WheelClackProfile` | private | - |
| `_audioSourceClack` | `IAudioSource[]` | private | - |
| `_lastClackNoise` | `float` | private | - |
| `_clackOffsets` | `float[]` | private | - |
| `_rollClackDistance` | `float` | private | - |
| `_clackOdometer` | `float` | private | - |
| `_absVelocity` | `float` | private | - |
| `_rollClackCoroutine` | `Coroutine` | private | - |
| `_carIsNearby` | `bool` | private | - |
| `_car` | `Car` | private | - |
| `MinRollClackVelocity` | `float` | private | `const` |

