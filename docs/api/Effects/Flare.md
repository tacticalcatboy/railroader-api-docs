# Flare Class

**Namespace:** `Effects`
**Source:** `Flare.cs`

## Declaration

```csharp
public class Flare : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `lightSource` | `Light` | public | - |
| `visualEffect` | `VisualEffect` | public | - |
| `fuseeRenderer` | `FuseeRenderer` | public | - |
| `_renderers` | `Renderer[]` | private | - |

