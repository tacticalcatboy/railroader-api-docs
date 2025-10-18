# GetTimetableDestinationsConfig Struct

**Namespace:** `Model.Ops`
**Source:** `PassengerStopTimetableLogic.cs`

## Declaration

```csharp
public struct GetTimetableDestinationsConfig
```

## Methods

### NoteDestination

```csharp
private bool NoteDestination(string stationCode, GameDateTime arrivalTime, int transferCount, string trainName)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MinimumStopDuration` | `int` | public | - |
| `DepartureImmediacyToCoefficient` | `AnimationCurve` | public | - |
| `DepartureImmediacyGrowthChance` | `AnimationCurve` | public | - |
| `DepartureImmediacyToMultiplier` | `AnimationCurve` | public | - |
| `DeparturePastToCoefficient` | `AnimationCurve` | public | - |
| `ArrivalTime` | `GameDateTime` | public | - |
| `TransferCount` | `int` | public | - |
| `BestTrainName` | `string` | public | - |
| `StartWaitingHours` | `int` | private | `const` |
| `EndWaitingHours` | `int` | private | `const` |

