# Entry Class

**Namespace:** `UI.Map`
**Source:** `MapBuilder.cs`

## Declaration

```csharp
private class Entry
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ShowSwitchStands` | `bool` | private | - |

## Methods

### CheckForSwitch

```csharp
private static bool CheckForSwitch(TrackSegment segment, out bool thrownAgainstA, out bool thrownAgainstB, out TrackNode switchNodeA, out TrackNode switchNodeB)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Segment` | `TrackSegment` | public | `readonly` |
| `Visibility` | `byte` | public | - |
| `mapCamera` | `Camera` | public | - |
| `splineMaterial` | `Material` | private | - |
| `mapSwitchStandPrefab` | `MapSwitchStand` | private | - |
| `segmentLineWidthMax` | `float` | public | - |
| `segmentLineWidthMin` | `float` | public | - |
| `windowSizeFactor` | `float` | public | - |
| `MinOrthoSize` | `float` | private | `const` |
| `MaxOrthoSize` | `float` | private | `const` |
| `trackTint` | `Color` | private | - |
| `trackMultMainline` | `float` | private | - |
| `trackMultBranch` | `float` | private | - |
| `trackMultIndustrial` | `float` | private | - |
| `trackMultUnavailable` | `float` | private | - |
| `_segmentLineWidth` | `float` | private | - |
| `_mapLayer` | `int` | private | `static` |
| `_container` | `Transform` | private | - |
| `_cullingGroup` | `CullingGroup` | private | - |
| `_cullingSpheres` | `BoundingSphere[]` | private | - |
| `_entries` | `List<Entry>` | private | - |
| `_mapIcons` | `HashSet<MapIcon>` | private | - |
| `_mapLabels` | `HashSet<MapLabel>` | private | - |
| `_materials` | `Queue<Material>` | private | `readonly` |
| `_shared` | `MapBuilder` | private | `static` |
| `_mapShowsSwitchesObserver` | `IDisposable` | private | - |
| `_mapShowsSwitches` | `bool` | private | - |
| `TrackColorMainline` | `Color` | private | - |
| `TrackColorBranch` | `Color` | private | - |
| `TrackColorIndustrial` | `Color` | private | - |
| `TrackColorUnavailable` | `Color` | private | - |
| `NormalizedScale` | `float` | private | - |
| `IconScale` | `float` | private | - |
| `SplineScaleMult` | `Vector3` | private | - |

