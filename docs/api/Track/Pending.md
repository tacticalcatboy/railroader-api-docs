# Pending Class

**Namespace:** `Track`
**Source:** `PrefabInstancer.cs`

## Declaration

```csharp
private class Pending
```

## Methods

### WorldDidMove

```csharp
private void WorldDidMove(WorldDidMoveEvent evt)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Matrixes` | `Matrix4x4[]` | public | - |
| `Count` | `int` | public | - |
| `Tokens` | `List<Token>` | public | - |
| `Prefab` | `Prefab` | public | - |
| `Offset` | `int` | public | - |
| `Length` | `int` | public | - |
| `Token` | `Token` | public | `readonly` |
| `Matrices` | `Matrix4x4[]` | public | `readonly` |
| `prefabManager` | `GPUInstancerPrefabManager` | private | - |
| `prefabs` | `GPUInstancerPrefab[]` | private | - |
| `AllPrefabs` | `Prefab[]` | private | `static` |
| `_entries` | `InstanceInfo[]` | private | - |
| `_coroutine` | `Coroutine` | private | - |

