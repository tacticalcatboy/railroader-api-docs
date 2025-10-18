# RepairRateState Struct

**Namespace:** `Model.Ops`
**Source:** `RepairTrack.cs`

## Declaration

```csharp
private struct RepairRateState
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `RateState` | `RepairRateState` | private | - |

## Methods

### CalculateRepairWork

```csharp
private static float CalculateRepairWork(Car car, float repairCapOverride, float? startCondition = null)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `PayRateMultiplier` | `float` | public | - |
| `PaidCurrent` | `bool` | public | - |
| `PayDue` | `float` | public | - |
| `TagOverhaul` | `string` | public | `const` |
| `RepairPartLbsPerRepairUnit` | `float` | private | `const` |
| `repairPartsLoad` | `Load` | private | - |
| `canOverhaul` | `bool` | public | - |
| `BasePayPerRepairUnit` | `float` | private | `const` |
| `VerySmallFloat` | `float` | private | `const` |
| `RepairCapLevels` | `int` | private | `const` |
| `PercentPerCapLevel` | `float` | private | `const` |
| `MaxPercentDropForCaps` | `float` | private | `const` |
| `RateStateKey` | `string` | private | - |
| `Config` | `Config` | private | `static` |

