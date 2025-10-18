# VirtualAudioSource Class

**Namespace:** `Audio`
**Source:** `VirtualAudioSource.cs`

## Declaration

```csharp
internal class VirtualAudioSource : IAudioSource
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `dopplerLevel` | `float` | public | - |

## Methods

### UpdateNearbyForDistanceBand

```csharp
public void UpdateNearbyForDistanceBand(int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `parentTransform` | `Transform` | internal | - |
| `parentOffset` | `Vector3` | internal | - |
| `cullDistance` | `AudioDistance` | internal | `readonly` |
| `_id` | `int` | private | `readonly` |
| `_name` | `string` | private | `readonly` |
| `_audioSource` | `AudioSource` | private | - |
| `_play` | `bool` | private | - |
| `_clip` | `AudioClip` | private | - |
| `_volume` | `float` | private | - |
| `_rolloffMode` | `AudioRolloffMode` | private | - |
| `_rolloffCurve` | `AnimationCurve` | private | - |
| `_minDistance` | `float` | private | - |
| `_maxDistance` | `float` | private | - |
| `_time` | `float` | private | - |
| `_pitch` | `float` | private | - |
| `_dopplerLevel` | `float` | private | - |
| `_spatialBlend` | `float` | private | - |
| `_loop` | `bool` | private | - |
| `_priority` | `int` | private | `readonly` |
| `_highPassFilter` | `AudioHighPassFilter` | private | - |
| `_lowPassFilter` | `AudioLowPassFilter` | private | - |
| `IsReal` | `bool` | public | - |

