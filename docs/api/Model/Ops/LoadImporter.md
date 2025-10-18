# LoadImporter Class

**Namespace:** `Model.Ops`
**Source:** `LoadImporter.cs`

## Declaration

```csharp
public class LoadImporter : IndustryComponent
```

## Methods

### OnCompleteWaybill

```csharp
protected override void OnCompleteWaybill(IIndustryContext ctx, IOpsCar car, Waybill waybill)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `load` | `Load` | public | - |
| `desiredCarCount` | `int` | public | - |
| `maxOrderCount` | `int` | public | - |
| `forwardToOnArrival` | `IndustryComponent` | public | - |

