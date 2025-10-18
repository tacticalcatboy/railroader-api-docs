# PrimeMoverAudioPlayer Class

**Namespace:** `Audio`
**Source:** `PrimeMoverAudioPlayer.cs`

## Declaration

```csharp
public class PrimeMoverAudioPlayer : MonoBehaviour, IPrimeMoverAudioPlayer
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Notch` | `int` | public | - |

## Methods

### WaitForSecondsOrUntilNotchChanges

```csharp
private IEnumerator WaitForSecondsOrUntilNotchChanges(float duration, int currentNotch)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `profile` | `PrimeMoverAudioProfile` | public | - |
| `_loopSourceA` | `IAudioSource` | private | - |
| `_loopSourceB` | `IAudioSource` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_notchFloat` | `float` | private | - |
| `_locomotive` | `BaseLocomotive` | private | - |
| `DebugText` | `string` | public | - |

