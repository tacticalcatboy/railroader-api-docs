# CurveMeshGenerator Class

**Namespace:** `BezierCurveMesh`
**Source:** `CurveMeshGenerator.cs`

## Declaration

```csharp
public static class CurveMeshGenerator
```

## Methods

### GenerateMeshAlongCurves

```csharp
public static Mesh GenerateMeshAlongCurves(Mesh segmentMesh, List<BezierCurve> curves, VectorAxis forwardAxis, Vector3 vertexScale)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SegmentCount` | `int` | public | - |
| `InputVertices` | `NativeArray<float3>` | public | - |
| `InputNormals` | `NativeArray<float3>` | public | - |
| `InputUVs` | `NativeArray<float2>` | public | - |
| `Curves` | `NativeArray<CubicBezierCurve>` | public | - |
| `CurveInfos` | `NativeArray<CurveSegmentInfo>` | public | - |
| `MeshLength` | `float` | public | - |
| `ForwardAxis` | `VectorAxis` | public | - |
| `VertexScale` | `float3` | public | - |
| `OutputVertices` | `NativeArray<float3>` | public | - |
| `OutputNormals` | `NativeArray<float3>` | public | - |
| `OutputUVs` | `NativeArray<float2>` | public | - |

