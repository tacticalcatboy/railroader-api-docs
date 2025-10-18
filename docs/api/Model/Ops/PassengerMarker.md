# PassengerMarker Struct

**Namespace:** `Model.Ops`
**Source:** `PassengerMarker.cs`

## Declaration

```csharp
public struct PassengerMarker
```

## Methods

### CountPassengersForStop

```csharp
public int CountPassengersForStop(string stopIdentifier)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Groups` | `List<PassengerGroup>` | public | `readonly` |
| `Destinations` | `HashSet<string>` | public | - |
| `LastStopIdentifier` | `string` | public | - |
| `AutoDestinationsFromTimetable` | `bool` | public | - |
| `TotalPassengers` | `int` | public | - |

