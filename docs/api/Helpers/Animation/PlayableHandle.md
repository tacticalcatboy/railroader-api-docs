# PlayableHandle Class

**Namespace:** `Helpers.Animation`
**Source:** `PlayableHandle.cs`

## Declaration

```csharp
public class PlayableHandle : IDisposable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Speed` | `float` | public | - |

## Methods

### Pause

```csharp
public void Pause()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_adapter` | `PlayableGraphAnimatorAdapter` | private | `readonly` |
| `_port` | `int` | private | `readonly` |
| `_playable` | `AnimationClipPlayable` | private | `readonly` |
| `PlayState` | `PlayState` | public | - |

