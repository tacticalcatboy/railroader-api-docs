# Industry Class

**Namespace:** `Model.Ops`
**Source:** `Industry.cs`

## Declaration

```csharp
public class Industry : GameBehaviour, IProgressionDisablable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Storage` | `IndustryStorageHelper` | public | - |

## Methods

### ApplyToBalance

```csharp
public void ApplyToBalance(int total, Ledger.Category category, string memo = null, int count = 0, bool quiet = false)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `identifier` | `string` | public | - |
| `usesContract` | `bool` | public | - |
| `_cachedComponents` | `IndustryComponent[]` | private | - |
| `_keyValueObject` | `IKeyValueObject` | private | - |
| `_tickCoroutine` | `Coroutine` | private | - |
| `ContractKey` | `string` | private | `const` |
| `NextContractKey` | `string` | private | `const` |
| `KeyReceivedCarCount` | `string` | private | `const` |
| `PerformanceHistoryKey` | `string` | private | `const` |
| `PerformanceHistoryLimit` | `int` | private | `const` |
| `TrackDisplayables` | `IEnumerable<IIndustryTrackDisplayable>` | public | - |
| `VisibleComponents` | `IEnumerable<IndustryComponent>` | public | - |
| `UniqueVisibleComponents` | `IEnumerable<IndustryComponent>` | public | - |
| `EntityReference` | `EntityReference` | public | - |
| `KeyValueObject` | `IKeyValueObject` | internal | - |

