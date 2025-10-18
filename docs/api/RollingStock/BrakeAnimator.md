# BrakeAnimator Class

**Namespace:** `RollingStock`
**Source:** `BrakeAnimator.cs`

## Declaration

```csharp
public class BrakeAnimator : MonoBehaviour, IBrakeAnimator
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BrakeApplied` | `bool` | public | - |

## Methods

### BrakeWasAppliedDidChange

```csharp
private void BrakeWasAppliedDidChange()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `animator` | `Animator` | public | - |
| `brakeAnimationClips` | `AnimationClip[]` | public | - |
| `_brakePlayables` | `PlayableHandle[]` | private | - |
| `_brakeWasApplied` | `bool` | private | - |

