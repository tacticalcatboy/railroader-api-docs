# SwitchGeometry Struct

**Namespace:** `Track`
**Source:** `SwitchGeometry.cs`

## Declaration

```csharp
public struct SwitchGeometry
```

## Methods

### AlignSwitchCurves

```csharp
private static void AlignSwitchCurves(SegmentProxy a, SegmentProxy b, out Vector3 origin, out BezierCurve aCurve, out BezierCurve bCurve)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `left` | `LineCurve` | public | - |
| `right` | `LineCurve` | public | - |
| `frogPoints` | `LinePoint[]` | public | - |
| `leftStockRail` | `LineCurve` | public | - |
| `rightStockRail` | `LineCurve` | public | - |
| `aClosureRail` | `LineCurve` | public | - |
| `bClosureRail` | `LineCurve` | public | - |
| `aPointRail` | `LineCurve` | public | - |
| `bPointRail` | `LineCurve` | public | - |
| `leftGuardRail` | `LineCurve` | public | - |
| `rightGuardRail` | `LineCurve` | public | - |
| `switchHome` | `Vector3` | public | - |
| `standRailCenter` | `Vector3` | public | - |
| `standPosition` | `Vector3` | public | - |
| `standRotation` | `Quaternion` | public | - |
| `FlangewayWidth` | `float` | private | `const` |
| `PointRailCutoff` | `float` | public | `const` |

