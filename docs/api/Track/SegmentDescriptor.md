# SegmentDescriptor Struct

**Namespace:** `Track`
**Source:** `TrackObjectManager.cs`

## Declaration

```csharp
private readonly struct SegmentDescriptor : ITrackDescriptor
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Identifier` | `string` | private | - |

## Methods

### BuildGameObject

```csharp
private GameObject BuildGameObject(ITrackDescriptor descriptor)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `prefabInstancer` | `PrefabInstancer` | private | - |
| `hideObjects` | `bool` | public | - |
| `_rebuilder` | `ITrackRebuilder` | private | - |
| `_graph` | `Graph` | private | - |
| `_builder` | `TrackObjectBuilder` | private | - |
| `_descriptors` | `Descriptors` | private | - |
| `_instance` | `TrackObjectManager` | private | `static` |
| `_pendingNodes` | `HashSet<TrackNode>` | private | `readonly` |
| `_invalidateCoroutine` | `CoroutineTask` | private | - |
| `_changeCount` | `int` | private | - |
| `Graph` | `Graph` | public | - |

