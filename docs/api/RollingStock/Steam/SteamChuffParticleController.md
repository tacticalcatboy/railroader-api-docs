# SteamChuffParticleController Class

**Namespace:** `RollingStock.Steam`
**Source:** `SteamChuffParticleController.cs`

## Declaration

```csharp
public class SteamChuffParticleController : MonoBehaviour, ISteamLocomotiveSubcomponent, IDynamicChuffDelegate
```

## Methods

### WhiteWithAlpha

```csharp
private return WhiteWithAlpha(white, alpha)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `visualEffect` | `VisualEffect` | public | - |
| `profile` | `ChuffProfile` | public | - |
| `tractiveEffort` | `float` | public | - |
| `absVelocity` | `float` | public | - |
| `continuous` | `bool` | public | - |
| `isStopped` | `bool` | public | - |
| `_targetTractiveEffort` | `float` | private | - |
| `_puffCoroutine` | `Coroutine` | private | - |
| `_smoke` | `SmokeEffectWrapper` | private | - |
| `_locomotive` | `BaseLocomotive` | private | - |
| `ParticlesEnabled` | `bool` | private | `static` |

