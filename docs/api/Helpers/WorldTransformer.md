# WorldTransformer Class

**Namespace:** `Helpers`
**Source:** `WorldTransformer.cs`

## Declaration

```csharp
public class WorldTransformer : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `WorldTransformer` | private | `static` |

## Methods

### TranslateParticleSystems

```csharp
private static void TranslateParticleSystems(Vector3 offset)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `tileRange` | `Vector2Int` | public | - |
| `MoveDelay` | `float` | private | `const` |
| `currentTile` | `Vector2Int` | private | - |
| `_currentOffset` | `Vector3` | private | `static` |
| `tileSize` | `Vector2` | public | - |
| `waitForMover` | `bool` | private | - |
| `_checkCoroutine` | `Coroutine` | private | - |
| `_scheduledMoveCoroutine` | `Coroutine` | private | - |
| `ObjectsToMove` | `HashSet<Transform>` | private | `static` |

