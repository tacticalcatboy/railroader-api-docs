# AutoEngineerFuelAlerter Class

**Namespace:** `Model.AI`
**Source:** `AutoEngineerFuelAlerter.cs`

## Declaration

```csharp
public class AutoEngineerFuelAlerter : MonoBehaviour
```

## Methods

### LoadCategoryForLoadId

```csharp
private static LoadCategory LoadCategoryForLoadId(string loadId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_locomotive` | `BaseLocomotive` | private | - |
| `_fuelCar` | `Car` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_thresholds` | `float[]` | private | `readonly` |
| `NoticeKeyFuel` | `string` | private | `const` |
| `NoticeKeyWater` | `string` | private | `const` |

