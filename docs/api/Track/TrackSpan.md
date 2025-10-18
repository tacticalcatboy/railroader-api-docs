# TrackSpan Class

**Namespace:** `Track`
**Source:** `TrackSpan.cs`

## Declaration

```csharp
public class TrackSpan : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsValid` | `bool` | public | - |

## Methods

### CalculateLengthFromCachedPoints

```csharp
private void CalculateLengthFromCachedPoints()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `_lower` | `SerializableLocation` | private | - |
| `_upper` | `SerializableLocation` | private | - |
| `_graph` | `Graph` | private | - |
| `_cachedPoints` | `List<Vector3>` | private | `readonly` |
| `_cachedSegments` | `List<TrackSegment>` | private | `readonly` |
| `_length` | `float` | private | - |
| `_warnedInvalid` | `bool` | private | - |
| `ColorEdit` | `Color` | public | `static` |
| `ColorLower` | `Color` | public | `static` |
| `ColorUpper` | `Color` | public | `static` |

