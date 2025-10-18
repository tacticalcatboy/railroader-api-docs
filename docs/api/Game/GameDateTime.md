# GameDateTime Struct

**Namespace:** `Game`
**Source:** `GameDateTime.cs`

## Declaration

```csharp
public struct GameDateTime
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TotalSeconds` | `double` | public | - |

## Methods

### AddingMinutes

```csharp
public GameDateTime AddingMinutes(int minutes)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HoursToSeconds` | `float` | private | `const` |
| `HoursToMinutes` | `float` | private | `const` |
| `SecondsToHours` | `float` | private | `const` |
| `DaysToSeconds` | `float` | private | `const` |
| `SecondsToDays` | `float` | private | `const` |
| `SecondsToMinutes` | `float` | private | `const` |
| `MinutesToHours` | `float` | private | `const` |
| `Day` | `int` | public | - |
| `Hours` | `float` | public | - |
| `Minutes` | `float` | public | - |
| `TotalHours` | `float` | public | - |
| `TotalDays` | `float` | public | - |
| `StartOfDay` | `GameDateTime` | public | - |
| `operator` | `bool` | public | `static` |

