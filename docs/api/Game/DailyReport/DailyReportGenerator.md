# DailyReportGenerator Class

**Namespace:** `Game.DailyReport`
**Source:** `DailyReportGenerator.cs`

## Declaration

```csharp
public class DailyReportGenerator : GameBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LatestReportMarkup` | `string` | public | - |

## Methods

### AddInventorySection

```csharp
private void AddInventorySection(StringBuilder sb)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_tickCoroutine` | `Coroutine` | private | - |
| `ObjectId` | `string` | private | `const` |
| `ReportHourOfDay` | `int` | private | `const` |
| `_instance` | `DailyReportGenerator` | private | `static` |
| `LastGeneratedKey` | `string` | private | `const` |
| `ReportKey` | `string` | private | `const` |
| `Now` | `GameDateTime` | private | `static` |

