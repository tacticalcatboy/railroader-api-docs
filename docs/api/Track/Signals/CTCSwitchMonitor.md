# CTCSwitchMonitor Class

**Namespace:** `Track.Signals`
**Source:** `CTCSwitchMonitor.cs`

## Declaration

```csharp
public class CTCSwitchMonitor : GameBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Switches` | `IEnumerable<TrackNode>` | private | - |

## Methods

### UpdateSwitchesForCTCDelayed

```csharp
private void UpdateSwitchesForCTCDelayed()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_observeSwitchesWhenReadyCoroutine` | `Coroutine` | private | - |
| `_updateSwitchesCoroutine` | `Coroutine` | private | - |
| `_storage` | `SignalStorage` | private | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |

