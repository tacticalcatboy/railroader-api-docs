# MarkerLampToggle Class

**Namespace:** `Effects`
**Source:** `MarkerLampToggle.cs`

## Declaration

```csharp
public class MarkerLampToggle : MonoBehaviour, IPickable
```

## Methods

### Activate

```csharp
public void Activate(PickableActivateEvent evt)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `lamp` | `MarkerLamp` | public | - |
| `keyBase` | `string` | public | - |
| `_positionObserver` | `IDisposable` | private | - |
| `_litObserver` | `IDisposable` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `KeyPosition` | `string` | private | - |
| `KeyLit` | `string` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

