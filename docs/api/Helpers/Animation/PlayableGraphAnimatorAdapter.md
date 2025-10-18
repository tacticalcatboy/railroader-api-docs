# PlayableGraphAnimatorAdapter Class

**Namespace:** `Helpers.Animation`
**Source:** `PlayableGraphAnimatorAdapter.cs`

## Declaration

```csharp
public class PlayableGraphAnimatorAdapter : MonoBehaviour
```

## Methods

### AddPlayable

```csharp
public int AddPlayable(AnimationClip clip, out AnimationClipPlayable playable)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `animator` | `Animator` | private | - |
| `_graph` | `PlayableGraph` | private | - |
| `_mixer` | `AnimationLayerMixerPlayable` | private | - |
| `_availablePorts` | `List<int>` | private | `readonly` |

