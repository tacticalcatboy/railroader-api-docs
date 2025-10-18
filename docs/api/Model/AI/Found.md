# Found Struct

**Namespace:** `Model.AI`
**Source:** `AutoEngineerPlanner.cs`

## Declaration

```csharp
internal struct Found
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsCTC` | `bool` | private | `static` |

## Methods

### RestorePassedSwitchesToOriginalPosition

```csharp
private void RestorePassedSwitchesToOriginalPosition()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SpeedMph` | `int` | public | - |
| `DistanceToSignal` | `float` | public | - |
| `SignalId` | `string` | public | `readonly` |
| `DistanceLimit` | `float` | public | - |
| `Behavior` | `OtherCarBehavior` | public | `readonly` |
| `CarId` | `string` | public | `readonly` |
| `Couple` | `bool` | public | - |
| `Avoid` | `OtherCarHandling` | public | `static` |
| `NoCouple` | `OtherCarHandling` | public | `static` |
| `AvailableDistance` | `float` | public | - |
| `AvailableDistanceReason` | `string` | public | - |
| `MaxSpeedMph` | `float` | public | - |
| `MaxSpeedMphNear` | `float` | public | - |
| `NextRestrictionDistance` | `float` | public | - |
| `AverageGrade` | `float` | public | - |
| `DistanceLimiter` | `DistanceLimiter` | public | - |
| `LimitingCarRelativeVelocity` | `float` | public | - |
| `Item` | `TItem` | public | `readonly` |
| `Location` | `Location` | public | `readonly` |
| `Distance` | `float` | public | `readonly` |
| `_engineer` | `AutoEngineer` | private | - |
| `_locomotive` | `BaseLocomotive` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_loopKeepalive` | `CoroutineKeepalive` | private | `readonly` |
| `_ordersObserver` | `IDisposable` | private | - |
| `_coupledCarsCached` | `List<Car>` | private | `readonly` |
| `_derailed` | `bool` | private | - |
| `_equipmentMaximumTrackCurvature` | `float` | private | - |
| `_maximumLength` | `float` | private | - |
| `_persistence` | `AutoEngineerPersistence` | private | - |
| `_orders` | `Orders` | private | - |
| `_manualStopObserver` | `IDisposable` | private | - |
| `_config` | `AutoEngineerConfig` | private | - |
| `_fuelAlerter` | `AutoEngineerFuelAlerter` | private | - |
| `_hotboxSpotter` | `AutoHotboxSpotter` | private | - |
| `_crossingSignaler` | `AutoEngineerCrossingSignaler` | private | - |
| `_passengerStopper` | `AutoEngineerPassengerStopper` | private | - |
| `_graph` | `Graph` | private | - |
| `_timetableController` | `TimetableController` | private | - |
| `_contextualIgnoreSignalId` | `string` | private | - |
| `_contextualIgnoreFlareId` | `string` | private | - |
| `_contextualBypassTimetableStation` | `string` | private | - |
| `_stopAndProceedSignalId` | `string` | private | - |
| `testKeepalive` | `bool` | private | - |
| `_routeCoroutine` | `Coroutine` | private | - |
| `_startStepIndex` | `int` | private | - |
| `_routeRequester` | `IPlayer` | private | - |
| `_underTrainPoints` | `List<Vector3>` | private | `readonly` |
| `_lastRouteWaypoint` | `OrderWaypoint` | private | - |
| `_waypointNoticeCleared` | `bool` | private | - |
| `_lastNotCurrentRouteReroute` | `float` | private | - |
| `ChangeDirectionPadding` | `float` | private | `const` |
| `drawRouteGizmos` | `bool` | private | - |
| `IsYardMode` | `bool` | internal | - |
| `BaseDistanceLimit` | `float` | private | - |

