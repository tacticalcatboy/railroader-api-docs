# IntegrationSet Class

**Namespace:** `Model.Physics`
**Source:** `IntegrationSet.cs`

## Declaration

```csharp
public class IntegrationSet
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ActiveCars` | `bool` | private | - |

## Methods

### ValidIndexOfCar

```csharp
private int ValidIndexOfCar(Car car)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `car` | `Car` | public | `readonly` |
| `position` | `float` | public | - |
| `oldPosition` | `float` | public | - |
| `acceleration` | `float` | public | - |
| `SlackA` | `float` | public | `readonly` |
| `SlackB` | `float` | public | `readonly` |
| `CarRadius` | `float` | public | `readonly` |
| `SlackStretch` | `float` | public | - |
| `SlackStretchDidChangeDirection` | `bool` | public | - |
| `PositionAtLastLocationUpdate` | `float` | public | - |
| `Velocity` | `float` | public | - |
| `Dirty` | `bool` | public | - |
| `LastSentTime` | `float` | public | - |
| `EventHandler` | `IIntegrationSetEventHandler` | private | `readonly` |
| `Id` | `uint` | public | `readonly` |
| `_elements` | `List<Element>` | protected | `readonly` |
| `_graph` | `Graph` | protected | `readonly` |
| `_lastTickPositioned` | `bool` | private | - |
| `_hasUpdatedBoundsOnce` | `bool` | private | - |
| `_ticksSinceRebuild` | `int` | private | - |
| `minCouplerSeparation` | `float` | private | `const` |
| `Cars` | `IEnumerable<Car>` | public | - |
| `IsEmpty` | `bool` | public | - |
| `NumberOfCars` | `int` | public | - |

