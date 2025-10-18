# Wheelset Class

**Namespace:** `RollingStock`
**Source:** `Wheelset.cs`

## Declaration

```csharp
public class Wheelset : MonoBehaviour, IBrakeAnimator
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BrakeApplied` | `bool` | public | - |

## Methods

### BrakeAppliedDidChange

```csharp
private void BrakeAppliedDidChange()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `wheels` | `List<Transform>` | internal | - |
| `diameterInInches` | `float` | internal | - |
| `animator` | `Animator` | internal | - |
| `applyBrakesAnimationClip` | `AnimationClip` | internal | - |
| `_brakeAppliedAnimationState` | `bool` | private | - |
| `_wheelAudio` | `WheelAudio` | private | - |
| `_localOdometer` | `float` | private | - |
| `_applyBrakesPlayable` | `PlayableHandle` | private | - |
| `_renderers` | `Renderer[]` | private | - |

