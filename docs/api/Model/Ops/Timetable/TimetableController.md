# TimetableController Class

**Namespace:** `Model.Ops.Timetable`
**Source:** `TimetableController.cs`

## Declaration

```csharp
public class TimetableController : GameBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CurrentDocument` | `TimetableDocument` | public | - |

## Methods

### SetCurrent

```csharp
public void SetCurrent(string content)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Source` | `string` | public | - |
| `Modified` | `GameDateTime` | public | - |
| `Author` | `string` | public | - |
| `branches` | `List<TimetableBranch>` | public | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_isInitialObservation` | `bool` | private | - |
| `_shared` | `TimetableController` | private | `static` |
| `_timetableObserver` | `IDisposable` | private | - |
| `_featureObserver` | `IDisposable` | private | - |
| `KeyValueIdentifier` | `string` | private | `const` |
| `KeyCurrent` | `string` | private | `const` |
| `CanEdit` | `bool` | public | `static` |

