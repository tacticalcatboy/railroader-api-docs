# CTCSignalCuller Class

**Namespace:** `Track.Signals`
**Source:** `CTCSignalCuller.cs`

## Declaration

```csharp
public class CTCSignalCuller : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `models` | `Transform[]` | public | - |
| `_cullRenderers` | `HashSet<Renderer>` | private | - |

