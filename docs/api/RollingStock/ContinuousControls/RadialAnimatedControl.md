# RadialAnimatedControl Class

**Namespace:** `RollingStock.ContinuousControls`
**Source:** `RadialAnimatedControl.cs`

## Declaration

```csharp
public class RadialAnimatedControl : ContinuousControl
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ControlComponentPurpose` | `ControlPurpose` | public | - |

## Methods

### UseAngleManipulation

```csharp
private bool UseAngleManipulation()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `rotationStart` | `float` | public | - |
| `rotationExtent` | `float` | public | - |
| `radius` | `float` | public | - |
| `momentary` | `bool` | public | - |
| `shiftActivateToggles` | `bool` | public | - |
| `homePosition` | `float` | public | - |
| `_clipPlayable` | `PlayableHandle` | private | - |
| `_mouseDownAngleVector` | `Vector3` | private | - |
| `_mouseDownAngle` | `float` | private | - |
| `_mouseDownValue` | `float` | private | - |
| `_animationValue` | `float` | private | - |
| `_useAngleManipulation` | `bool` | private | - |
| `_cameraLocalControlPosition` | `Vector3` | private | - |
| `_cameraLocalControlUp` | `Vector3` | private | - |
| `_cameraLocalControlHandle` | `Vector3` | private | - |
| `_activatedAt` | `float` | private | - |
| `_deactivatedAt` | `float` | private | - |
| `_camera` | `Camera` | private | - |
| `_debugPlanePoint` | `Vector3` | private | - |
| `_activeCoroutine` | `Coroutine` | private | - |
| `_animateToValueCoroutine` | `Coroutine` | private | - |

