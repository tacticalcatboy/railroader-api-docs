# TimeSynchronizer Class

**Namespace:** `Network.Client`
**Source:** `TimeSynchronizer.cs`

## Declaration

```csharp
public class TimeSynchronizer : MonoBehaviour
```

## Methods

### Send

```csharp
private void Send()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Client` | `GameClient` | public | - |
| `_tickOffset` | `long` | private | - |
| `_timeSyncSentAt` | `long` | private | - |
| `NumPings` | `int` | private | `const` |
| `_offsets` | `CircularBuffer<long>` | private | - |
| `Tick` | `long` | public | - |

