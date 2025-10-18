# PanelField Struct

**Namespace:** `Model.Ops`
**Source:** `IndustryComponent.cs`

## Declaration

```csharp
public struct PanelField
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ProgressionDisabled` | `bool` | public | - |

## Methods

### OnCompleteWaybill

```csharp
protected virtual void OnCompleteWaybill(IIndustryContext ctx, IOpsCar car, Waybill waybill)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Label` | `string` | public | `readonly` |
| `Text` | `string` | public | `readonly` |
| `Tooltip` | `string` | public | `readonly` |
| `subIdentifier` | `string` | public | - |
| `_identifier` | `string` | private | - |
| `trackSpans` | `TrackSpan[]` | public | - |
| `carTypeFilter` | `CarTypeFilter` | public | - |
| `sharedStorage` | `bool` | public | - |
| `_cachedIndustry` | `Industry` | private | - |
| `TrackSpans` | `IEnumerable<TrackSpan>` | public | - |

