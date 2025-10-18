# SceneryAssetInstance Class

**Namespace:** `Helpers`
**Source:** `SceneryAssetInstance.cs`

## Declaration

```csharp
public class SceneryAssetInstance : MonoBehaviour, CullingManager.ICullingEventHandler
```

## Methods

### FindInstancesOfIdentifier

```csharp
public static IEnumerable<SceneryAssetInstance> FindInstancesOfIdentifier(string identifier)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `identifier` | `string` | public | - |
| `_modelLoadTask` | `Task<LoadedAssetReference<GameObject>>` | private | - |
| `_wantsLoaded` | `bool` | private | - |
| `_model` | `GameObject` | private | - |
| `_definitionIdentifier` | `string` | private | - |
| `_definition` | `SceneryDefinition` | private | - |
| `_cullRenderers` | `HashSet<Renderer>` | private | `readonly` |
| `_cullingVisible` | `bool` | private | - |

