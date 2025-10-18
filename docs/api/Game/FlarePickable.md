# FlarePickable Class

**Namespace:** `Game`
**Source:** `FlarePickable.cs`

## Declaration

```csharp
public class FlarePickable : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TooltipInfo` | `TooltipInfo` | public | - |

## Methods

### Configure

```csharp
public void Configure(string flareId, PlayerId placedBy)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_placedBy` | `PlayerId` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

