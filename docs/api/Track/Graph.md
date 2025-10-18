# Graph Class

**Namespace:** `Track`
**Source:** `Graph.cs`

## Declaration

```csharp
public class Graph : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TurntableControllers` | `IEnumerable<TurntableController>` | public | - |

## Methods

### CheckSameRoute

```csharp
private bool CheckSameRoute(Location cursor, Location target, TrackSegment.End end, float limit, out float actualDistance)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `enabledGroupIds` | `List<string>` | public | - |
| `availableGroupIds` | `List<string>` | public | - |
| `_segmentCurveCache` | `SegmentCache` | private | `readonly` |
| `_segmentsReachableFromOthers` | `List<TrackSegment>` | private | `readonly` |
| `_cachedTurntableControllers` | `HashSet<TurntableController>` | private | - |
| `SampleCurveUncachedSamples` | `int` | private | `const` |
| `_pendingTrackMarkers` | `HashSet<TrackMarker>` | private | `readonly` |
| `Nodes` | `IEnumerable<TrackNode>` | public | - |
| `Segments` | `IEnumerable<TrackSegment>` | public | - |

