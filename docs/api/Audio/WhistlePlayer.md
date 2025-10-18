# WhistlePlayer Class

**Namespace:** `Audio`
**Source:** `WhistlePlayer.cs`

## Declaration

```csharp
public class WhistlePlayer : MonoBehaviour
```

## Methods

### Configure

```csharp
public void Configure(AudioClip audioClip)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `profile` | `WhistleProfile` | public | - |
| `parameter` | `float` | public | - |
| `_parameterSmooth` | `float` | private | - |
| `_parameter` | `float` | private | - |
| `_airSpeed` | `float` | private | - |
| `_audioSource` | `IAudioSource` | private | - |
| `_ownedClip` | `AudioClip` | private | - |
| `rampUpPitch` | `float` | private | - |
| `lerpSpeed` | `float` | private | - |
| `airLerpSpeed` | `float` | private | - |
| `parameterToPitch` | `AnimationCurve` | private | - |
| `parameterToVolume` | `AnimationCurve` | private | - |

