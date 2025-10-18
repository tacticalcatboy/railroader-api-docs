# ReputationTracker Class

**Namespace:** `Game.Reputation`
**Source:** `ReputationTracker.cs`

## Declaration

```csharp
public class ReputationTracker : GameBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LastUpdatedDay` | `int` | private | - |

## Methods

### KeyForPassengerStopEdge

```csharp
public static string KeyForPassengerStopEdge(string fromId, string toId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_tickCoroutine` | `Coroutine` | private | - |
| `ObjectId` | `string` | private | `const` |
| `_instance` | `ReputationTracker` | private | `static` |
| `LastDayKey` | `string` | private | `const` |
| `ReputationKey` | `string` | private | `const` |
| `ReputationReportKey` | `string` | private | `const` |
| `KeyDerailmentHours` | `string` | private | `const` |
| `Now` | `GameDateTime` | private | `static` |

