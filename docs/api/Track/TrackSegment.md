# TrackSegment Class

**Namespace:** `Track`
**Source:** `TrackSegment.cs`

## Declaration

```csharp
public class TrackSegment : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Curve` | `BezierCurve` | public | - |

## Methods

### GetLength

```csharp
public float GetLength()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `a` | `TrackNode` | public | - |
| `b` | `TrackNode` | public | - |
| `priority` | `int` | public | - |
| `speedLimit` | `int` | public | - |
| `groupId` | `string` | public | - |
| `style` | `Style` | public | - |
| `trackClass` | `TrackClass` | public | - |
| `turntable` | `Turntable` | public | - |
| `_posRotCache` | `BezierDistanceParameterCache` | private | - |
| `_gizmosApproximation` | `LinePoint[]` | private | - |
| `IsInvisible` | `bool` | public | - |

