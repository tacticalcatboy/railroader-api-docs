# SwitchStand Class

**Namespace:** `Track`
**Source:** `SwitchStand.cs`

## Declaration

```csharp
public class SwitchStand : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DisplayThrown` | `bool` | private | - |

## Methods

### Configure

```csharp
public void Configure(TrackNode node)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `animator` | `Animator` | public | - |
| `animationClip` | `AnimationClip` | public | - |
| `animationSpeed` | `float` | public | - |
| `supressThrownAnimation` | `bool` | public | - |
| `audioClip` | `AudioClip` | public | - |
| `_node` | `TrackNode` | private | - |
| `_wasThrown` | `bool` | private | - |
| `_playable` | `PlayableHandle` | private | - |
| `playableTargetSpeed` | `float` | private | - |

