# BaseLocomotive Class

**Namespace:** `Model`
**Source:** `BaseLocomotive.cs`

## Declaration

```csharp
public abstract class BaseLocomotive : Car
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsIdle` | `bool` | public | - |

## Methods

### UpdateTractiveEffortWheelState

```csharp
private void UpdateTractiveEffortWheelState()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `cabControls` | `LocomotiveCabControlsHookup` | public | - |
| `locomotiveControl` | `LocomotiveControlAdapter` | public | - |
| `_tractiveEffort` | `float` | private | - |
| `_wheelVelocity` | `float` | protected | - |
| `_wheelState` | `CarWheelState` | private | - |
| `_periodicUpdateCoroutine` | `Coroutine` | private | - |
| `_idleTimerLastReset` | `float` | private | - |
| `slipSpeed` | `float` | public | - |
| `LocomotiveBrakeNegative` | `float` | private | `const` |
| `IsMuEnabled` | `bool` | internal | - |

