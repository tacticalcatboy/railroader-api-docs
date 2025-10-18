# Entry Class

**Namespace:** `Track`
**Source:** `TrackRebuilder.cs`

## Declaration

```csharp
private class Entry
```

## Methods

### SetInitialVisibility

```csharp
private void SetInitialVisibility(Entry entry)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `isInRange` | `bool` | public | - |
| `isVisible` | `bool` | public | - |
| `gameObject` | `GameObject` | public | - |
| `maskObject` | `GameObject` | public | - |
| `_group` | `CullingGroup` | private | - |
| `_destroyQueue` | `List<Entry>` | private | `readonly` |
| `_buildQueue` | `List<Entry>` | private | `readonly` |
| `InitialSphereCount` | `int` | private | `const` |
| `_spheres` | `BoundingSphere[]` | private | - |
| `_sphereEntries` | `Entry[]` | private | - |
| `_sphereCount` | `int` | private | - |
| `_distanceBands` | `float[]` | private | `readonly` |
| `_lastOffset` | `Vector3` | private | - |
| `_lastReport` | `float` | private | - |

