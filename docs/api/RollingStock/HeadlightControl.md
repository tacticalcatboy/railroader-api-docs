# HeadlightControl Class

**Namespace:** `RollingStock`
**Source:** `HeadlightControl.cs`

## Declaration

```csharp
public class HeadlightControl : MonoBehaviour
```

## Methods

### StringForUnidirectional

```csharp
private static string StringForUnidirectional(HeadlightController.State state)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `control` | `RadialAnimatedControl` | public | - |
| `style` | `HeadlightControlStyle` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_carId` | `string` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_headlightKey` | `string` | private | - |
| `_controlDidChange` | `bool` | private | - |
| `CarId` | `string` | private | - |
| `SnapPoints` | `int` | private | - |

