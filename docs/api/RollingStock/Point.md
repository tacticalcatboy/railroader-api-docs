# Point Struct

**Namespace:** `RollingStock`
**Source:** `Hose.cs`

## Declaration

```csharp
private struct Point
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OnGetPressure` | `Func<float>` | public | - |

## Methods

### UpdateEdges

```csharp
private void UpdateEdges()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `Vector3` | public | - |
| `OldPosition` | `Vector3` | public | - |
| `Acceleration` | `Vector3` | public | - |
| `_connectedTo` | `Hose` | private | - |
| `_firstConnectedTo` | `bool` | private | - |
| `_damping` | `float` | private | - |
| `meshRenderer` | `MeshRenderer` | public | - |
| `profile` | `HoseProfile` | public | - |
| `_hoseLength` | `float` | private | - |
| `NumPoints` | `int` | private | `const` |
| `_points` | `Point[]` | private | `readonly` |
| `_lastUpdatePoints` | `Vector3[]` | private | `readonly` |
| `_propulsion` | `float` | private | - |
| `EdgeCount` | `int` | private | `const` |
| `_splinePoints` | `Vector3[]` | private | - |
| `_splineRotations` | `Quaternion[]` | private | - |
| `_gladhand` | `Transform` | private | - |
| `_isVisible` | `bool` | private | - |
| `_meshBuilder` | `TubeMeshBuilder` | private | - |
| `EndPoint` | `Vector3` | private | - |
| `EndRotation` | `Quaternion` | private | - |
| `EdgeLength` | `float` | private | - |

