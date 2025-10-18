# Interchange Class

**Namespace:** `Model.Ops`
**Source:** `Interchange.cs`

## Declaration

```csharp
public class Interchange : IndustryComponent
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Disabled` | `bool` | public | - |

## Methods

### CarLengths

```csharp
private int CarLengths(TrackSpan span)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Orders` | `List<IOrder>` | public | `readonly` |
| `Loaders` | `InterchangedIndustryLoader[]` | private | - |
| `ServeHour` | `int` | private | `static` |
| `NumberOfCarsOrdered` | `int` | private | - |

