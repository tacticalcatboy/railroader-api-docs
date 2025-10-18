# EqFilter Class

**Namespace:** `Audio.Filters`
**Source:** `EqFilter.cs`

## Declaration

```csharp
public class EqFilter : MonoBehaviour
```

## Methods

### OnAudioFilterRead

```csharp
private void OnAudioFilterRead(float[] data, int channels)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_filters` | `BiQuadFilter[]` | private | `readonly` |
| `centerFrequency` | `float` | public | - |
| `bandwidth` | `float` | public | - |
| `dbGain` | `float` | public | - |

