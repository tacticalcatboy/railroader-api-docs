# AutoHotboxSpotter Class

**Namespace:** `Model.AI`
**Source:** `AutoHotboxSpotter.cs`

## Declaration

```csharp
public class AutoHotboxSpotter : AutoEngineerComponentBase
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasCars` | `bool` | private | - |

## Methods

### UpdateHotboxRestriction

```csharp
private void UpdateHotboxRestriction()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_spotterCoroutine` | `Coroutine` | private | - |
| `_removerCoroutine` | `Coroutine` | private | - |
| `_cars` | `IReadOnlyList<Car>` | private | - |
| `_knownHotboxes` | `HashSet<Car>` | private | `readonly` |

