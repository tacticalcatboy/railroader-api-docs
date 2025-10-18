# WireSet Class

**Namespace:** `TelegraphPoles`
**Source:** `TelegraphPoleManager.cs`

## Declaration

```csharp
private class WireSet
```

## Methods

### BuildPole

```csharp
private void BuildPole(SimpleGraph.Runtime.SimpleGraph graph, Node node)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `polePrefabs` | `List<TelegraphPole>` | private | - |
| `wirePrefab` | `TelegraphWire` | private | - |
| `_enabledTags` | `HashSet<int>` | private | `readonly` |
| `_rebuildCoroutine` | `Coroutine` | private | - |
| `debugDrawHeights` | `bool` | public | - |
| `_cullingGroup` | `CullingGroup` | private | - |
| `_spheres` | `BoundingSphere[]` | private | - |
| `_cullingDistances` | `float[]` | private | `readonly` |
| `MinDistanceBand` | `int` | private | `const` |

