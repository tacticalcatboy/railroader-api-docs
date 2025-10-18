# Coupler Class

**Namespace:** `RollingStock`
**Source:** `Coupler.cs`

## Declaration

```csharp
public class Coupler : MonoBehaviour
```

## Methods

### SlackIn

```csharp
public void SlackIn(float slackDiffNormalized)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Inset` | `float` | public | `const` |
| `car` | `Car` | public | - |
| `pickable` | `CouplerPickable` | public | - |
| `audioClipClose` | `AudioClip` | public | - |
| `audioClipOpen` | `AudioClip` | public | - |
| `openCloseAnimationClip` | `AnimationClip` | public | - |
| `animator` | `Animator` | public | - |
| `_controller` | `TrainController` | private | - |
| `_playableGraph` | `PlayableGraph` | private | - |
| `_openClosePlayable` | `AnimationClipPlayable` | private | - |
| `_meshRenderers` | `MeshRenderer[]` | private | - |
| `slackInClip` | `AudioClip` | public | - |
| `slackOutClip` | `AudioClip` | public | - |

