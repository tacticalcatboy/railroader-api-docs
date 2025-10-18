# CTCBlock Class

**Namespace:** `Track.Signals`
**Source:** `CTCBlock.cs`

## Declaration

```csharp
public class CTCBlock : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Interlocking` | `CTCInterlocking` | public | - |

## Methods

### TrySetDirection

```csharp
public bool TrySetDirection(CTCDirection propagateDirection, CTCTrafficFilter newTrafficFilter, bool dryRun = false)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `thrownSwitchesSetOccupied` | `bool` | public | - |
| `_updateCoroutine` | `Coroutine` | private | - |
| `_storage` | `SignalStorage` | private | - |
| `_spans` | `TrackSpan[]` | private | - |
| `_thrownNodeIds` | `HashSet<string>` | private | `readonly` |
| `_unlockedNodeIds` | `HashSet<string>` | private | `readonly` |
| `_testForceOccupied` | `bool` | private | - |
| `Storage` | `SignalStorage` | private | - |
| `IsCTC` | `bool` | private | - |
| `Spans` | `TrackSpan[]` | private | - |

