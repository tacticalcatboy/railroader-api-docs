# VirtualAudioSourcePool Class

**Namespace:** `Audio`
**Source:** `VirtualAudioSourcePool.cs`

## Declaration

```csharp
public class VirtualAudioSourcePool : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Instance` | `VirtualAudioSourcePool` | private | `static` |

## Methods

### ActualReturnAfterFinished

```csharp
private void ActualReturnAfterFinished(IAudioSource audioSource)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_instance` | `VirtualAudioSourcePool` | private | `static` |
| `_cullingGroup` | `CullingGroup` | private | - |
| `_spheres` | `BoundingSphere[]` | private | - |
| `_sources` | `List<VirtualAudioSource>` | private | `readonly` |
| `_returnAfterFinished` | `List<VirtualAudioSource>` | private | `readonly` |
| `_sequence` | `int` | private | - |
| `GlobalDopplerLevel` | `float` | internal | `static` |

