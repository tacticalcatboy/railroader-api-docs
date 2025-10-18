# PrimeMover Class

**Namespace:** `Model.Physics`
**Source:** `PrimeMover.cs`

## Declaration

```csharp
public class PrimeMover : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasFuel` | `bool` | public | - |

## Methods

### CalculateTractiveEffort

```csharp
private static float CalculateTractiveEffort(float mph, float startingTractiveEffort)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `startingTractiveEffort` | `int` | public | - |
| `running` | `bool` | public | - |
| `reverser` | `int` | public | - |
| `notch` | `int` | public | - |
| `tractiveEffort` | `float` | public | - |
| `amps` | `float` | public | - |
| `rpms` | `float` | public | - |
| `MaxAmps` | `int` | private | `const` |
| `_notchToRpm` | `int[]` | private | `readonly` |
| `_notchToPowerPercent` | `float[]` | private | `readonly` |
| `actualPowerPercent` | `float` | private | - |
| `NormalizedTractiveEffort` | `float` | public | - |

