# CylinderCockController Class

**Namespace:** `Effects`
**Source:** `CylinderCockController.cs`

## Declaration

```csharp
public class CylinderCockController : MonoBehaviour, ISteamLocomotiveSubcomponent
```

## Methods

### UpdateCoroutine

```csharp
private IEnumerator UpdateCoroutine()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `smokeEffects` | `VisualEffect[]` | private | - |
| `smokeOutputCurve` | `AnimationCurve` | private | - |
| `audioClip` | `AudioClip` | private | - |
| `volumeCurve` | `AnimationCurve` | private | - |
| `audioDistanceMin` | `float` | private | - |
| `audioDistanceMax` | `float` | private | - |
| `_locomotive` | `BaseLocomotive` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_open` | `bool` | private | - |
| `_controlObserver` | `IDisposable` | private | - |
| `_forwardOffset` | `float` | private | - |
| `_audioSources` | `IAudioSource[]` | private | - |
| `_phase` | `float` | private | - |
| `_radius` | `float` | private | - |
| `_steam` | `float` | private | - |
| `_lastOffTime` | `float` | private | - |

