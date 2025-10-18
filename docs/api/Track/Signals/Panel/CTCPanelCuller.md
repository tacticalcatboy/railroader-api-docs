# CTCPanelCuller Class

**Namespace:** `Track.Signals.Panel`
**Source:** `CTCPanelCuller.cs`

## Declaration

```csharp
public class CTCPanelCuller : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_cullRenderers` | `HashSet<Renderer>` | private | - |
| `_cullCanvases` | `HashSet<Canvas>` | private | - |

