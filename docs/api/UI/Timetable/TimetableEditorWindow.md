# TimetableEditorWindow Class

**Namespace:** `UI.Timetable`
**Source:** `TimetableEditorWindow.cs`

## Declaration

```csharp
public class TimetableEditorWindow : MonoBehaviour, IProgrammaticWindow, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### HandleWindowRequestClose

```csharp
private void HandleWindowRequestClose()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `_timetableController` | `TimetableController` | private | - |
| `_visualEditor` | `VisualTimetableEditor` | private | - |
| `WindowIdentifier` | `string` | public | - |
| `DefaultSize` | `Vector2Int` | public | - |
| `Shared` | `TimetableEditorWindow` | public | `static` |

