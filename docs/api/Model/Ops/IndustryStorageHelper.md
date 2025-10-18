# IndustryStorageHelper Class

**Namespace:** `Model.Ops`
**Source:** `IndustryStorageHelper.cs`

## Declaration

```csharp
public class IndustryStorageHelper : IPropertyAccessControlDelegate
```

## Methods

### ObserveInterchangeExtraScheduledChanged

```csharp
public IDisposable ObserveInterchangeExtraScheduledChanged(Action action)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_keyValueObject` | `IKeyValueObject` | private | `readonly` |
| `_id` | `string` | private | `readonly` |
| `StorageKey` | `string` | private | `const` |
| `KeyHadUnfulfilledOrders` | `string` | private | `const` |
| `KeyInterchangeExtraScheduled` | `string` | private | `const` |
| `KeyInterchangeLastServiced` | `string` | private | `const` |
| `KeyWarnings` | `string` | private | `const` |
| `InterchangeDisabled` | `bool` | public | - |
| `CanScheduleExtra` | `bool` | public | - |

