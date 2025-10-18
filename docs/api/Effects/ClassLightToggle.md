# ClassLightToggle Class

**Namespace:** `Effects`
**Source:** `ClassLightToggle.cs`

## Declaration

```csharp
public class ClassLightToggle : MonoBehaviour, IPickable
```

## Methods

### Activate

```csharp
public void Activate(PickableActivateEvent evt)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `lamp` | `ClassLight` | public | - |
| `keyBase` | `string` | public | - |
| `_colorObserver` | `IDisposable` | private | - |
| `_litObserver` | `IDisposable` | private | - |
| `keyValueObject` | `KeyValueObject` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |

