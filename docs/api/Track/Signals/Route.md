# Route Struct

**Namespace:** `Track.Signals`
**Source:** `CTCInterlocking.cs`

## Declaration

```csharp
public struct Route
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Direction` | `SignalDirection` | public | - |

## Methods

### IsLined

```csharp
private bool IsLined(Route route)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `switchFilters` | `List<SwitchFilter>` | public | - |
| `outletLeft` | `int` | public | - |
| `outletRight` | `int` | public | - |
| `direction` | `CTCDirection` | public | - |
| `blocks` | `List<CTCBlock>` | public | - |
| `nextSignal` | `CTCSignal` | public | - |
| `id` | `string` | public | - |
| `displayName` | `string` | public | - |
| `switchSets` | `List<SwitchSet>` | public | - |
| `outlets` | `List<Outlet>` | public | - |
| `routes` | `List<Route>` | public | - |
| `_blocks` | `IReadOnlyList<CTCBlock>` | private | - |
| `_storage` | `SignalStorage` | private | - |
| `_directionObserver` | `IDisposable` | private | - |
| `_routeBlockObservers` | `HashSet<IDisposable>` | private | `readonly` |

