# TrackMarker Class

**Namespace:** `Track`
**Source:** `TrackMarker.cs`

## Declaration

```csharp
public class TrackMarker : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `PassengerStop` | `PassengerStop` | public | - |

## Methods

### InvalidateCache

```csharp
public void InvalidateCache()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `type` | `TrackMarkerType` | public | - |
| `_location` | `SerializableLocation` | private | - |
| `_warnedInvalid` | `bool` | private | - |
| `_signal` | `CTCSignal` | private | - |
| `_passengerStop` | `PassengerStop` | private | - |
| `Graph` | `Graph` | internal | - |
| `ColorEdit` | `Color` | public | `static` |
| `ColorLower` | `Color` | public | `static` |

