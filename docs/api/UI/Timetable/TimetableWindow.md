# TimetableWindow Class

**Namespace:** `UI.Timetable`
**Source:** `TimetableWindow.cs`

## Declaration

```csharp
public class TimetableWindow : MonoBehaviour, IProgrammaticWindow, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### AddTrainCell

```csharp
private void AddTrainCell(UIPanelBuilder uIPanelBuilder, Model.Ops.Timetable.Timetable.Train train)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `_timetableController` | `TimetableController` | private | - |
| `_allStations` | `string[]` | private | - |
| `_firstBuild` | `bool` | private | - |
| `ColWidthStation` | `float` | private | `const` |
| `ColWidthTrain` | `int` | private | `const` |
| `WindowIdentifier` | `string` | public | - |
| `DefaultSize` | `Vector2Int` | public | - |
| `Shared` | `TimetableWindow` | public | `static` |

