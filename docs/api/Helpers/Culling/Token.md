# Token Class

**Namespace:** `Helpers.Culling`
**Source:** `CullingManager.cs`

## Declaration

```csharp
public class Token : IDisposable
```

## Methods

### AddSphere

```csharp
public Token AddSphere(Vector3 worldPosition, float radius, ICullingEventHandler handler)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Handler` | `ICullingEventHandler` | public | - |
| `Manager` | `CullingManager` | public | `readonly` |
| `Index` | `int` | public | `readonly` |
| `_cullingGroup` | `CullingGroup` | private | - |
| `_spheres` | `BoundingSphere[]` | private | - |
| `_tokens` | `List<Token>` | private | - |
| `_distances` | `float[]` | private | - |
| `_managerName` | `string` | private | - |
| `_nextSphere` | `int` | private | - |
| `_sphereCount` | `int` | private | - |
| `_needsUpdate` | `HashSet<Token>` | private | `readonly` |
| `Hose` | `CullingManager` | public | `static` |
| `Bridge` | `CullingManager` | public | `static` |
| `CTC` | `CullingManager` | public | `static` |
| `Signal` | `CullingManager` | public | `static` |
| `Scenery` | `CullingManager` | public | `static` |
| `Flare` | `CullingManager` | public | `static` |

