# KeyValueAdjacentCopier Class

**Namespace:** `RollingStock.Controls`
**Source:** `KeyValueAdjacentCopier.cs`

## Declaration

```csharp
public class KeyValueAdjacentCopier : MonoBehaviour
```

## Methods

### TryGetAdjacentCar

```csharp
private bool TryGetAdjacentCar(out Car adjacent)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `keys` | `List<string>` | public | - |
| `_subscriptions` | `List<IDisposable>` | private | - |
| `_car` | `Car` | private | - |
| `_adjacentId` | `string` | private | - |

