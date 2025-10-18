# GameStorage Class

**Namespace:** `Game.State`
**Source:** `GameStorage.cs`

## Declaration

```csharp
public class GameStorage : IPropertyAccessControlDelegate
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OilFeature` | `bool` | public | - |

## Methods

### ObserveOverhaulMiles

```csharp
public IDisposable ObserveOverhaulMiles(Action<int> action)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_gameKeyValueObject` | `KeyValueObject` | private | `readonly` |
| `ObjectId` | `string` | public | `const` |
| `KeyMode` | `string` | public | `const` |
| `KeyDefaultAccessLevel` | `string` | private | `const` |
| `KeyAllowNewPlayers` | `string` | private | `const` |
| `KeyPasswordHash` | `string` | private | `const` |
| `RailroadNameMaxLength` | `int` | public | `const` |
| `ReportingMarkMaxLength` | `int` | public | `const` |
| `ReportingMarkRegex` | `string` | public | `const` |
| `RoadNumberMaxLength` | `int` | public | `const` |
| `KeyBalance` | `string` | private | `const` |
| `KeyTimeMultiplier` | `string` | private | `const` |
| `TrainCrewMembershipRequiredKey` | `string` | private | `const` |
| `TrainCrewMembershipManagedByTrainmasterKey` | `string` | private | `const` |
| `KeyLoanAmount` | `string` | private | `const` |
| `KeyNextInterestDate` | `string` | private | `const` |
| `KeyLoanNextInterestOffset` | `string` | private | `const` |
| `KeyUnbilledRunDuration` | `string` | private | `const` |
| `KeyInterchangeServeHour` | `string` | private | `const` |
| `KeyInterchangeShuffle` | `string` | private | `const` |
| `KeyPassengerLimit` | `string` | private | `const` |
| `KeyBrakeForce` | `string` | private | `const` |
| `KeyAICrossingSignal` | `string` | private | `const` |
| `KeyAIPassengerStopEnable` | `string` | private | `const` |
| `KeyAIPassengerStopMinimumStopDuration` | `string` | private | `const` |
| `KeyAICallSignals` | `string` | private | `const` |
| `KeyWearFeature` | `string` | private | `const` |
| `KeyOilFeature` | `string` | public | `const` |
| `KeyOverhaulMiles` | `string` | private | `const` |
| `KeyWearMultiplier` | `string` | private | `const` |
| `KeyOilUseMultiplier` | `string` | private | `const` |
| `KeyMapShowsSwitches` | `string` | private | `const` |
| `KeyTimetableFeature` | `string` | private | `const` |
| `HasNewPlayerPassword` | `bool` | public | - |
| `CanWriteInterchangeShuffle` | `bool` | public | `static` |
| `CanWriteBrakeForce` | `bool` | public | `static` |

