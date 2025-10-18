# IndustryContext Struct

**Namespace:** `Model.Ops`
**Source:** `IndustryContext.cs`

## Declaration

```csharp
public readonly struct IndustryContext : IIndustryContext
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `PortionOfDayUntilNextRegularService` | `float` | public | - |

## Methods

### OrderWeightInTons

```csharp
private static int OrderWeightInTons(TypedContainerItem<CarDefinition> definitionInfo, [CanBeNull] Load load)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Descriptor` | `CarDescriptor` | public | `readonly` |
| `CarId` | `string` | public | `readonly` |
| `_trainController` | `TrainController` | private | `readonly` |
| `_controller` | `OpsController` | private | `readonly` |
| `_keyValueObject` | `IKeyValueObject` | private | `readonly` |
| `_industry` | `Industry` | private | `readonly` |
| `_industryComponent` | `IndustryComponent` | private | `readonly` |
| `_sizePreference` | `CarSizePreference` | private | `readonly` |
| `Storage` | `IndustryStorageHelper` | private | - |

