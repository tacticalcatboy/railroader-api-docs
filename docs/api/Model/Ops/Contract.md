# Contract Struct

**Namespace:** `Model.Ops`
**Source:** `Contract.cs`

## Declaration

```csharp
public readonly struct Contract
```

## Methods

### TimelyDeliveryBonus

```csharp
public int TimelyDeliveryBonus(int days, int basePayment)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Tier` | `int` | public | `readonly` |
| `TimelyDeliveryMaxDays` | `int` | public | `const` |
| `TierKey` | `string` | private | `const` |
| `Percent` | `float` | public | - |
| `SpeedBonus` | `float` | public | - |
| `PropertyValue` | `Value` | public | - |

