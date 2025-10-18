# AutoEngineerPassengerStopper Class

**Namespace:** `Model.AI`
**Source:** `AutoEngineerPassengerStopper.cs`

## Declaration

```csharp
public class AutoEngineerPassengerStopper : AutoEngineerComponentBase
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsStoppedAtStation` | `bool` | public | - |

## Methods

### GetEarlyLateString

```csharp
private static string GetEarlyLateString(int offsetMinutes)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_nextStopText` | `string` | private | - |
| `_nextStop` | `PassengerStop` | private | - |
| `_pendingDepartureTimetableCode` | `string` | private | - |
| `_coupledCars` | `List<Car>` | private | - |
| `_cachedPassengerStopIds` | `HashSet<string>` | private | `readonly` |
| `_cachedHasCoaches` | `bool` | private | - |
| `_wasStopped` | `bool` | private | - |
| `_stopAnnounceTime` | `GameDateTime` | private | - |
| `_departAnnounceTime` | `GameDateTime` | private | - |
| `_timetableWaitAnnounceTime` | `GameDateTime` | private | - |
| `_lastMarkersHashCode` | `int` | private | - |
| `_markersHashChanged` | `GameDateTime` | private | - |
| `_didStartBell` | `bool` | private | - |
| `_arrivalTime` | `GameDateTime` | private | - |
| `AnnounceTimeout` | `float` | private | `const` |
| `TimetableWaitAnnounceTimeout` | `float` | private | `const` |
| `MarkersHashChangeTimeout` | `float` | private | `const` |
| `ArrivalBellDistance` | `float` | private | `const` |
| `StopRadius` | `float` | private | `const` |
| `Now` | `GameDateTime` | private | `static` |
| `Enable` | `bool` | private | `static` |
| `MinimumStopDuration` | `float` | private | `static` |
| `IsTimetableTrain` | `bool` | private | - |

