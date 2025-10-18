# SmbPitchShifter Class

**Namespace:** `Audio.DynamicChuff`
**Source:** `SmbPitchShifter.cs`

## Declaration

```csharp
public class SmbPitchShifter
```

## Methods

### ShortTimeFourierTransform

```csharp
public void ShortTimeFourierTransform(float[] fftBuffer, long fftFrameSize, long sign)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MAX_FRAME_LENGTH` | `int` | private | `static` |
| `gInFIFO` | `float[]` | private | - |
| `gOutFIFO` | `float[]` | private | - |
| `gFFTworksp` | `float[]` | private | - |
| `gLastPhase` | `float[]` | private | - |
| `gSumPhase` | `float[]` | private | - |
| `gOutputAccum` | `float[]` | private | - |
| `gAnaFreq` | `float[]` | private | - |
| `gAnaMagn` | `float[]` | private | - |
| `gSynFreq` | `float[]` | private | - |
| `gSynMagn` | `float[]` | private | - |
| `gRover` | `long` | private | - |

