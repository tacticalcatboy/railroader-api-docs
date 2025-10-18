# VisualTimetableEditor Class

**Namespace:** `UI.Timetable`
**Source:** `VisualTimetableEditor.cs`

## Declaration

```csharp
public class VisualTimetableEditor : BaseTimetableEditor
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasUnsavedChanges` | `bool` | public | - |

## Methods

### NormalizeTrainSymbol

```csharp
private static string NormalizeTrainSymbol(string symbol)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_selectedTrainName` | `string` | private | - |
| `_stationsEastToWest` | `IReadOnlyList<string>` | private | - |
| `_stationsWestToEast` | `IReadOnlyList<string>` | private | - |
| `_timetableLoadSaveHelper` | `TimetableLoadSaveHelper` | private | `readonly` |
| `_pendingCloseRequest` | `bool` | private | - |

