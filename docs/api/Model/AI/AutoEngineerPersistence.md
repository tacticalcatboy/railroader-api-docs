# AutoEngineerPersistence Struct

**Namespace:** `Model.AI`
**Source:** `AutoEngineerPersistence.cs`

## Declaration

```csharp
public struct AutoEngineerPersistence
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ContextualOrders` | `List<ContextualOrder>` | public | - |

## Methods

### ObservePlannerStatusChanged

```csharp
public IDisposable ObservePlannerStatusChanged(Action action)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_object` | `KeyValueObject` | private | `readonly` |
| `AutoEngineerOrdersKey` | `string` | public | `const` |
| `AutoEngineerContextualOrdersKey` | `string` | public | `const` |
| `AutoEngineerManualStopDistanceKey` | `string` | private | `const` |
| `AutoEngineerPlannerStatus` | `string` | public | `const` |
| `AutoEngineerPassModeStatus` | `string` | private | `const` |

