# CTCPanelLamp Class

**Namespace:** `Track.Signals`
**Source:** `CTCPanelLamp.cs`

## Declaration

```csharp
public class CTCPanelLamp : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TooltipInfo` | `TooltipInfo` | public | - |

## Methods

### Deactivate

```csharp
public void Deactivate()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `lampRenderer` | `MeshRenderer` | public | - |
| `modelTransform` | `Transform` | public | - |
| `palette` | `LensPalette` | public | - |
| `color` | `Color` | public | - |
| `mode` | `Mode` | public | - |
| `targetId` | `string` | public | - |
| `filterValue` | `int` | public | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_lit` | `bool` | private | - |
| `_lampMaterial` | `Material` | private | - |
| `_cachedTooltipInfo` | `TooltipInfo` | private | - |
| `_cachedTooltipExpires` | `float` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

