# DerailedParticleController Class

**Namespace:** `RollingStock`
**Source:** `DerailedParticleController.cs`

## Declaration

```csharp
public class DerailedParticleController : MonoBehaviour, ICarMovementListener
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CarVelocity` | `float` | private | - |

## Methods

### UpdateSmoke

```csharp
private void UpdateSmoke()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `visualEffect` | `VisualEffect` | private | - |
| `profile` | `SmokeEffectProfile` | private | - |
| `_value` | `float` | private | - |
| `_playing` | `bool` | private | - |
| `_smoke` | `SmokeEffectWrapper` | private | - |
| `_derailmentTarget` | `float` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `MinDerailValue` | `float` | private | `const` |
| `MinVelocity` | `float` | private | `const` |
| `ParticlesEnabled` | `bool` | private | `static` |

