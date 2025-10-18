# OpsCarAdapter Struct

**Namespace:** `Model.Ops`
**Source:** `OpsCarAdapter.cs`

## Declaration

```csharp
public readonly struct OpsCarAdapter : IOpsCar
```

## Methods

### Load

```csharp
public float Load(Load load, float quantityToLoad)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_car` | `Car` | private | `readonly` |
| `_loadSlots` | `List<LoadSlot>` | private | `readonly` |
| `_opsCarPositionResolver` | `IOpsCarPositionResolver` | private | `readonly` |
| `Id` | `string` | public | - |
| `CarType` | `string` | public | - |
| `DisplayName` | `string` | public | - |
| `IsOwnedByPlayer` | `bool` | public | - |
| `Condition` | `float` | public | - |
| `WeightInTons` | `int` | public | - |

