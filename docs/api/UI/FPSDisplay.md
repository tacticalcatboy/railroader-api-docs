# FPSDisplay Class

**Namespace:** `UI`
**Source:** `FPSDisplay.cs`

## Declaration

```csharp
public class FPSDisplay : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Run` | `bool` | public | - |

## Methods

### CalculatePercentiles

```csharp
private void CalculatePercentiles()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_run` | `bool` | private | - |
| `label` | `TMP_Text` | private | - |
| `displayMode` | `DisplayMode` | public | - |
| `refreshPeriod` | `float` | private | - |
| `gradient` | `Gradient` | private | - |
| `FrameBufferSize` | `int` | private | `const` |
| `_frameTimes` | `List<float>` | private | `readonly` |
| `_sortedFrameTimes` | `List<float>` | private | `readonly` |
| `GoodFrameDuration` | `float` | private | `const` |
| `BadFrameDuration` | `float` | private | `const` |
| `_frames` | `int` | private | - |
| `_duration` | `float` | private | - |
| `_onePercentLowDuration` | `float` | private | - |
| `_onePercentHighDuration` | `float` | private | - |

