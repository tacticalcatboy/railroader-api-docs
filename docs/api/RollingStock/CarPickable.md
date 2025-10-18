# CarPickable Class

**Namespace:** `RollingStock`
**Source:** `CarPickable.cs`

## Declaration

```csharp
public class CarPickable : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TooltipInfo` | `TooltipInfo` | public | - |

## Methods

### TooltipTitle

```csharp
private string TooltipTitle()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `car` | `Car` | public | - |
| `_cachedTooltipText` | `string` | private | - |
| `_cachedTooltipTextTime` | `float` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

