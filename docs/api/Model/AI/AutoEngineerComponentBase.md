# AutoEngineerComponentBase Class

**Namespace:** `Model.AI`
**Source:** `AutoEngineerComponentBase.cs`

## Declaration

```csharp
public abstract class AutoEngineerComponentBase : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Planner` | `AutoEngineerPlanner` | protected | - |

## Methods

### ApplyMovement

```csharp
public abstract void ApplyMovement(MovementInfo info)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_locomotive` | `BaseLocomotive` | protected | - |
| `_planner` | `AutoEngineerPlanner` | private | - |
| `_config` | `AutoEngineerConfig` | protected | - |

