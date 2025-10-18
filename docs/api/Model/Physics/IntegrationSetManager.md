# IntegrationSetManager Class

**Namespace:** `Model.Physics`
**Source:** `IntegrationSetManager.cs`

## Declaration

```csharp
public class IntegrationSetManager : IEnumerable<IntegrationSet>, IEnumerable
```

## Methods

### RemoveCar

```csharp
public void RemoveCar(Car car)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_idCursor` | `uint` | private | - |
| `_integrationSetsToRemove` | `List<uint>` | private | `readonly` |
| `_deltaAdded` | `HashSet<uint>` | private | `readonly` |
| `_deltaRemoved` | `HashSet<uint>` | private | `readonly` |
| `_deltaChanged` | `HashSet<uint>` | private | `readonly` |
| `_needsBatchPositionUpdate` | `HashSet<IntegrationSet>` | private | - |

