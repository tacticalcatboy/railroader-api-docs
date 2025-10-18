# CTCSignal Class

**Namespace:** `Track.Signals`
**Source:** `CTCSignal.cs`

## Declaration

```csharp
public abstract class CTCSignal : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Interlocking` | `CTCInterlocking` | public | - |

## Methods

### CalculateAspect

```csharp
protected abstract SignalAspect CalculateAspect(out StopReason stopReason)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `id` | `string` | public | - |
| `headConfiguration` | `SignalHeadConfiguration` | public | - |
| `direction` | `CTCDirection` | public | - |
| `modelController` | `CTCSignalModelController` | public | - |
| `Storage` | `SignalStorage` | protected | - |
| `Observers` | `HashSet<IDisposable>` | protected | `readonly` |
| `_scheduledUpdate` | `Coroutine` | private | - |
| `IsCTC` | `bool` | protected | - |
| `IsIntermediate` | `bool` | public | - |
| `CurrentAspect` | `SignalAspect` | public | - |

