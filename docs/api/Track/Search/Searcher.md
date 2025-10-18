# Searcher Class

**Namespace:** `Track.Search`
**Source:** `Searcher.cs`

## Declaration

```csharp
internal class Searcher
```

## Methods

### AddLocationToOpenList

```csharp
private void AddLocationToOpenList(AStar<SearchState>.GetNeighborsContext ctx, Location location, StepDirection direction, float distance, float cost, IEnumerable<ClearSwitch> addClearSwitches = null)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_graph` | `Graph` | private | `readonly` |
| `_origin` | `Location` | private | `readonly` |
| `_destination` | `Location` | private | `readonly` |
| `_checkForCars` | `bool` | private | `readonly` |
| `_checkForCarsIgnored` | `HashSet<Car>` | private | `readonly` |
| `_checkForCarsImpasse` | `HashSet<Car>` | private | `readonly` |
| `_limitSwitchIds` | `HashSet<string>` | private | `readonly` |
| `_trainLength` | `float` | private | `readonly` |
| `_trainMomentum` | `float` | private | `readonly` |
| `_mustClearSwitches` | `bool` | private | `readonly` |
| `_enableLogging` | `bool` | private | `readonly` |
| `_costs` | `HeuristicCosts` | private | `readonly` |
| `_clearSwitchesScratch0` | `HashSet<ClearSwitch>` | private | `readonly` |
| `_clearSwitchesEmpty` | `IEnumerable<ClearSwitch>` | private | `readonly` |

