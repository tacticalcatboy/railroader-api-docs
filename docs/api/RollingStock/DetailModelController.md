# DetailModelController Class

**Namespace:** `RollingStock`
**Source:** `DetailModelController.cs`

## Declaration

```csharp
public class DetailModelController : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### CullingSphereStateChanged

```csharp
public void CullingSphereStateChanged(bool isVisible, int distanceBand)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_car` | `Car` | private | - |
| `_renderers` | `List<Renderer>` | private | `readonly` |
| `_modelLoadCancellationTokenSource` | `CancellationTokenSource` | private | - |
| `_modelLoadReferences` | `List<LoadedAssetReference<GameObject>>` | private | `readonly` |

