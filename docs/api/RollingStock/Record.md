# Record Class

**Namespace:** `RollingStock`
**Source:** `CarCuller.cs`

## Declaration

```csharp
private class Record
```

## Methods

### TeardownCarCullingGroup

```csharp
private void TeardownCarCullingGroup()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Car` | `Car` | public | `readonly` |
| `LoadToken` | `IDisposable` | public | - |
| `trainController` | `TrainController` | public | - |
| `_cullingGroup` | `CullingGroup` | private | - |
| `_spheres` | `BoundingSphere[]` | private | - |
| `_records` | `List<Record>` | private | - |
| `DistanceBandClose` | `int` | public | `const` |
| `DistanceBandNearby` | `int` | public | `const` |
| `DistanceBandLoadModel` | `int` | public | `const` |
| `DistanceBandNoChange` | `int` | public | `const` |
| `DistanceBandUnloadModel` | `int` | public | `const` |
| `_distanceBands` | `float[]` | private | `readonly` |

