# ChuffFilter Class

**Namespace:** `RollingStock.Steam`
**Source:** `ChuffFilter.cs`

## Declaration

```csharp
public class ChuffFilter : MonoBehaviour
```

## Methods

### GetNextChuffDelay

```csharp
public float GetNextChuffDelay()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `EngineSpeed` | `float` | public | - |
| `EngineCutoff` | `float` | public | - |
| `EngineThrottle` | `float` | public | - |
| `_highPassFilter` | `AudioHighPassFilter` | private | - |
| `_lowPassFilter` | `AudioLowPassFilter` | private | - |
| `_reverbFilter` | `AudioReverbFilter` | private | - |
| `curve` | `AnimationCurve` | private | - |
| `engineSpeed` | `float` | public | - |
| `engineCutoff` | `float` | public | - |
| `engineSize` | `float` | public | - |
| `engineThrottle` | `float` | public | - |
| `engineNormalizedTE` | `float` | public | - |
| `profile` | `ChuffFilterProfile` | private | - |
| `enableUpdateCurve` | `bool` | private | - |
| `_running` | `bool` | private | - |
| `_sampleRate` | `int` | private | - |
| `_sampleTime` | `float` | private | - |
| `_lowPassModulationTime` | `float` | private | - |
| `_lowPassBase` | `float` | private | - |
| `_highPassBase` | `float` | private | - |
| `_engineVolume` | `float` | private | - |
| `_parameters` | `Parameters` | private | - |
| `_parameterLock` | `object` | private | `readonly` |
| `_loggedNaNCoeff` | `bool` | private | `static` |

