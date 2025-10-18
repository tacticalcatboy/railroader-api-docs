# ClockDriver Class

**Namespace:** `Effects`
**Source:** `ClockDriver.cs`

## Declaration

```csharp
public class ClockDriver : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Instance` | `ClockDriver` | public | `static` |

## Methods

### OnDestroy

```csharp
private void OnDestroy()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_onTime` | `float` | private | `readonly` |
| `_offTime` | `float` | private | `readonly` |
| `Action` | `Action<bool>` | public | `readonly` |
| `IsOn` | `bool` | public | - |
| `DisposeAction` | `Action` | public | - |
| `_coroutine` | `Coroutine` | private | - |
| `_items` | `HashSet<Item>` | private | `readonly` |
| `HourOfDay` | `float` | private | - |

