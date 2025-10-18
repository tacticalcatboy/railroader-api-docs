# Turntable Class

**Namespace:** `Track`
**Source:** `Turntable.cs`

## Declaration

```csharp
public class Turntable : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Graph` | `Graph` | private | - |

## Methods

### NodeIsDeadEnd

```csharp
public bool NodeIsDeadEnd(TrackNode node, out Vector3 direction)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `radius` | `float` | public | - |
| `subdivisions` | `int` | public | - |
| `nodes` | `List<TrackNode>` | private | - |
| `defaultStopIndex` | `int` | private | - |
| `bridgeGroupId` | `string` | private | - |
| `_segment` | `TrackSegment` | private | - |
| `_freeA` | `TrackNode` | private | - |
| `_freeB` | `TrackNode` | private | - |
| `_needsInitialize` | `bool` | private | - |
| `_graph` | `Graph` | private | - |
| `IsLined` | `bool` | public | - |
| `DegreesPerIndex` | `float` | private | - |

