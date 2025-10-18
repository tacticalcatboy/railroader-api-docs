# Train Class

**Namespace:** `Model.Ops.Timetable`
**Source:** `Timetable.cs`

## Declaration

```csharp
public class Train
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DisplayStringLong` | `string` | public | - |

## Methods

### Equals

```csharp
private return Equals(other)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Name` | `string` | public | - |
| `Direction` | `Direction` | public | - |
| `TrainClass` | `TrainClass` | public | - |
| `TrainType` | `TrainType` | public | - |
| `Entries` | `List<Entry>` | public | `readonly` |
| `Station` | `string` | public | `readonly` |
| `DepartureTime` | `TimetableTime` | public | - |
| `Meets` | `IReadOnlyList<string>` | public | - |

