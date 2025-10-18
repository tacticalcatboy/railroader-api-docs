# TimeWindow Class

**Namespace:** `UI`
**Source:** `TimeWindow.cs`

## Declaration

```csharp
public class TimeWindow : MonoBehaviour, IProgrammaticWindow, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### GetSleepValues

```csharp
private void GetSleepValues(out GameDateTime now, out int targetHour, out float hoursToSleep)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `WindowIdentifier` | `string` | public | - |
| `DefaultSize` | `Vector2Int` | public | - |
| `Shared` | `TimeWindow` | public | `static` |

