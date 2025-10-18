# Entry Struct

**Namespace:** `RollingStock`
**Source:** `MovingColliderScaler.cs`

## Declaration

```csharp
private struct Entry
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `MovingColliderScaler` | public | `static` |

## Methods

### Unregister

```csharp
public void Unregister(CapsuleCollider theCollider)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Valid` | `bool` | public | - |
| `Collider` | `CapsuleCollider` | public | `readonly` |
| `Transform` | `Transform` | public | `readonly` |
| `LastPosition` | `Vector3` | public | - |
| `ColliderRadius0` | `float` | public | `readonly` |
| `_shared` | `MovingColliderScaler` | private | `static` |
| `maxScale` | `float` | private | - |
| `speedLow` | `float` | private | - |
| `speedHigh` | `float` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_colliders` | `List<Entry>` | private | `readonly` |
| `_nextFreeSlot` | `int` | private | - |

