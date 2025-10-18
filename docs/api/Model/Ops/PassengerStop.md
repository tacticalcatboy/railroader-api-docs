# PassengerStop Class

**Namespace:** `Model.Ops`
**Source:** `PassengerStop.cs`

## Declaration

```csharp
public class PassengerStop : GameBehaviour, IIndustryTrackDisplayable, IProgressionDisablable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TimetableName` | `string` | public | - |

## Methods

### CarIsAtPassengerStop

```csharp
public bool CarIsAtPassengerStop(Car car, TrainController trainController)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Groups` | `IReadOnlyList<WaitingPassengerGroup>` | public | `readonly` |
| `Total` | `int` | public | `readonly` |
| `LastPaymentTime` | `float` | public | - |
| `Count` | `int` | public | - |
| `Amount` | `float` | public | - |
| `DistanceInMiles` | `float` | public | - |
| `TraverseTimeSeconds` | `float` | public | - |
| `Success` | `bool` | public | `readonly` |
| `identifier` | `string` | public | - |
| `timetableCode` | `string` | public | - |
| `basePopulation` | `int` | public | - |
| `flagStop` | `bool` | public | - |
| `neighbors` | `PassengerStop[]` | public | - |
| `passengerLoad` | `Load` | public | - |
| `_spans` | `TrackSpan[]` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_observer` | `IDisposable` | private | - |
| `_timetableName` | `string` | private | - |
| `_allPassengerStops` | `PassengerStop[]` | private | `static` |
| `_lastGrow` | `GameDateTime` | private | - |
| `_loop` | `Coroutine` | private | - |
| `_workingCarIds` | `HashSet<string>` | private | `readonly` |
| `_availableDestinations` | `HashSet<PassengerStop>` | private | - |
| `GrowInterval` | `int` | private | `const` |
| `StateKey` | `string` | private | `const` |
| `GroupWindowSeconds` | `double` | internal | `const` |
| `_markers` | `HashSet<TrackMarker>` | private | - |
| `_pendingPayment` | `PendingPayment` | private | `readonly` |
| `_levelsByHour` | `float[]` | private | `readonly` |
| `MaxWaiting` | `int` | private | - |
| `Now` | `GameDateTime` | private | `static` |
| `KeyValueIdentifier` | `string` | private | - |
| `ActiveAvailableDestinations` | `IEnumerable<PassengerStop>` | private | - |
| `PaymentTime` | `float` | private | `static` |
| `DisplayName` | `string` | public | - |
| `IsVisible` | `bool` | public | - |
| `TrackSpans` | `IEnumerable<TrackSpan>` | public | - |

