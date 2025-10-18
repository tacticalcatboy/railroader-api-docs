# BrakeStandController Class

**Namespace:** `RollingStock`
**Source:** `BrakeStandController.cs`

## Declaration

```csharp
public class BrakeStandController : MonoBehaviour
```

## Methods

### StyleDidChange

```csharp
private void StyleDidChange(BrakeStyle newStyle)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `style` | `BrakeStyle` | public | - |
| `trainBrakeControl` | `RadialAnimatedControl` | public | - |
| `locomotiveBrakeControl` | `RadialAnimatedControl` | public | - |
| `cutoutControl` | `RadialAnimatedControl` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_deactivated` | `HashSet<GameObject>` | private | `readonly` |
| `DefaultBrakeStyle` | `BrakeStyle` | private | `static` |

