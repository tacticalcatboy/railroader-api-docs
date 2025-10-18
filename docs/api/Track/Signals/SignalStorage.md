# SignalStorage Class

**Namespace:** `Track.Signals`
**Source:** `SignalStorage.cs`

## Declaration

```csharp
public class SignalStorage : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SystemMode` | `SystemMode` | public | - |

## Methods

### ObserveSignalAspect

```csharp
public IDisposable ObserveSignalAspect(string signalId, Action<SignalAspect> action)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_keyValueObject` | `KeyValueObject` | private | - |
| `KeyUnlockedSwitchIds` | `string` | private | `const` |
| `KeyValueObject` | `KeyValueObject` | private | - |

