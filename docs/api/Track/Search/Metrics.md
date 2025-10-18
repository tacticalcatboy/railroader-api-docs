# Metrics Struct

**Namespace:** `Track.Search`
**Source:** `RouteSearch.cs`

## Declaration

```csharp
public struct Metrics
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `Vector3` | public | - |

## Methods

### WithLocation

```csharp
public Step WithLocation(Location newLocation, float newDistance)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Iterations` | `int` | public | - |
| `Distance` | `float` | public | - |
| `Node` | `TrackNode` | public | `readonly` |
| `Direction` | `StepDirection` | public | `readonly` |
| `Distance` | `float` | public | `readonly` |
| `Flags` | `StepFlag` | public | `readonly` |
| `_graph` | `Graph` | private | `readonly` |

