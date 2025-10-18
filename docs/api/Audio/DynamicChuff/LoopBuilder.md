# LoopBuilder Class

**Namespace:** `Audio.DynamicChuff`
**Source:** `LoopBuilder.cs`

## Declaration

```csharp
internal class LoopBuilder
```

## Methods

### Envelope

```csharp
private static float Envelope(float parameter, float center)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_sourceSamples` | `float[][]` | private | `readonly` |
| `_sourceNumSamples` | `int` | private | `readonly` |
| `_outputFrequency` | `int` | private | `readonly` |
| `chuffsPerRevolution` | `int` | private | `const` |
| `_pitchShifter` | `SmbPitchShifter` | private | - |
| `_highPassFilter` | `BiQuadFilter` | private | `readonly` |
| `_lowPassFilter` | `BiQuadFilter` | private | `readonly` |
| `Frequency` | `int` | public | - |

