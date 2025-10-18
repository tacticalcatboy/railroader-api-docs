# ContinuousControl Class

**Namespace:** `RollingStock.ContinuousControls`
**Source:** `ContinuousControl.cs`

## Declaration

```csharp
public abstract class ContinuousControl : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MaxPickDistance` | `float` | public | - |

## Methods

### Snap

```csharp
protected float Snap(float param)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `displayName` | `string` | public | - |
| `value` | `float` | protected | - |
| `CheckAuthorized` | `Func<bool>` | public | - |
| `tooltipText` | `Func<string>` | public | - |
| `ChangeThreshold` | `float` | public | - |
| `_isActive` | `bool` | protected | - |
| `_lastSentValue` | `float` | private | - |
| `_lastSentTime` | `float` | private | - |
| `ZeroThreshold` | `float` | protected | `const` |
| `Priority` | `int` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |

