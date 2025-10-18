# VerticalControl Class

**Namespace:** `RollingStock.ContinuousControls`
**Source:** `VerticalControl.cs`

## Declaration

```csharp
public class VerticalControl : ContinuousControl
```

## Methods

### CalculateParameter

```csharp
private bool CalculateParameter(out float newParameter)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `animationClip` | `AnimationClip` | public | - |
| `animator` | `Animator` | public | - |
| `momentary` | `bool` | public | - |
| `_clipPlayable` | `PlayableHandle` | private | - |
| `_clipPlayablePort` | `int` | private | - |
| `_mouseDownValue` | `float` | private | - |
| `_animationValue` | `float` | private | - |
| `_camera` | `Camera` | private | - |
| `_mousePositionAtDown` | `Vector3` | private | - |

