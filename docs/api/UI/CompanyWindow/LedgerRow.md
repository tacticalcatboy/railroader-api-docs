# LedgerRow Class

**Namespace:** `UI.CompanyWindow`
**Source:** `LedgerRow.cs`

## Declaration

```csharp
public class LedgerRow : MonoBehaviour, ILazyScrollListCell
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ListIndex` | `int` | public | - |

## Methods

### Configure

```csharp
private void Configure()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Type` | `RowType` | public | - |
| `Date` | `string` | public | - |
| `Category` | `string` | public | - |
| `PayeeMemo` | `string` | public | - |
| `Amount` | `string` | public | - |
| `Balance` | `string` | public | - |
| `ExtraTrailing` | `float` | public | - |
| `dateLabel` | `TMP_Text` | private | - |
| `categoryLabel` | `TMP_Text` | private | - |
| `payeeMemoLabel` | `TMP_Text` | private | - |
| `amountLabel` | `TMP_Text` | private | - |
| `balanceLabel` | `TMP_Text` | private | - |
| `_info` | `Info` | private | - |
| `RectTransform` | `RectTransform` | public | - |

