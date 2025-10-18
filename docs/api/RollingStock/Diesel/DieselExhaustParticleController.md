# DieselExhaustParticleController Class

**Namespace:** `RollingStock.Diesel`
**Source:** `DieselExhaustParticleController.cs`

## Declaration

```csharp
public class DieselExhaustParticleController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `NormalizedExhaustOutput` | `float` | public | - |

## Methods

### UpdateSmoke

```csharp
private void UpdateSmoke()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `visualEffect` | `VisualEffect` | public | - |
| `profile` | `SmokeEffectProfile` | public | - |
| `accelInfluenceLow` | `float` | public | - |
| `accelInfluenceHigh` | `float` | public | - |
| `_value` | `float` | private | - |
| `_accel` | `float` | private | - |
| `_smoke` | `SmokeEffectWrapper` | private | - |
| `_locomotive` | `BaseLocomotive` | private | - |
| `ParticlesEnabled` | `bool` | private | `static` |

