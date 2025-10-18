# TrackObjectBuilder Class

**Namespace:** `Track`
**Source:** `TrackObjectBuilder.cs`

## Declaration

```csharp
public class TrackObjectBuilder
```

## Methods

### CreateMeshObject

```csharp
private GameObject CreateMeshObject(Mesh mesh, string objectName, GameObject parent)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `Vector3` | public | - |
| `Rotation` | `Quaternion` | public | `readonly` |
| `TagGenerated` | `string` | public | `const` |
| `TieSpacing` | `float` | private | `const` |
| `_profile` | `TrackMeshProfile` | private | `readonly` |
| `_meshHideFlags` | `HideFlags` | private | `readonly` |
| `_parent` | `GameObject` | private | `readonly` |
| `_trackLayer` | `int` | private | `readonly` |
| `_prefabInstancer` | `PrefabInstancer` | private | `readonly` |
| `_warnedMissingTieInstancer` | `bool` | private | - |

