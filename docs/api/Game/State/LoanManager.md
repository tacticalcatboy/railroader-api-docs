# LoanManager Class

**Namespace:** `Game.State`
**Source:** `LoanManager.cs`

## Declaration

```csharp
public class LoanManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LoanNextInterestOffset` | `int` | private | - |

## Methods

### HandleOffsetLoan

```csharp
private void HandleOffsetLoan(int loanDeltaAmount)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_gameStorage` | `GameStorage` | private | - |
| `_updateCoroutine` | `Coroutine` | private | - |
| `InterestPercent` | `float` | private | `const` |
| `InterestPaymentIntervalDays` | `int` | private | `const` |
| `Now` | `GameDateTime` | private | `static` |
| `CanRequestLoanChange` | `bool` | public | `static` |

