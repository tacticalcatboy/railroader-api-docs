# InstanceEntry Struct

**Namespace:** `Helpers`
**Source:** `InstancedMeshDrawer.cs`

## Declaration

```csharp
private struct InstanceEntry
```

## Methods

### OnDisable

```csharp
private void OnDisable()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `Matrix4x4` | public | - |
| `Inverse` | `Matrix4x4` | public | - |
| `Control` | `Vector4` | public | - |
| `SizeInBytes` | `int` | public | `const` |
| `mesh` | `Mesh` | public | - |
| `subMeshIndex` | `int` | public | - |
| `material` | `Material` | public | - |
| `instances` | `Matrix4x4[]` | public | - |
| `_positionBuffer` | `ComputeBuffer` | private | - |
| `_argsBuffer` | `ComputeBuffer` | private | - |
| `_args` | `uint[]` | private | - |
| `_lastPosition` | `Vector3` | private | - |
| `_cachedInstanceCount` | `int` | private | - |
| `_cachedSubMeshIndex` | `int` | private | - |
| `_bounds` | `Bounds` | private | - |
| `_propertyBlock` | `MaterialPropertyBlock` | private | - |

