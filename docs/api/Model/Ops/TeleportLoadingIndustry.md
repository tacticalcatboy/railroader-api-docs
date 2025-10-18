# TeleportLoadingIndustry Class

**Namespace:** `Model.Ops`
**Source:** `TeleportLoadingIndustry.cs`

## Declaration

```csharp
public class TeleportLoadingIndustry : IndustryLoaderBase
```

## Methods

### ApplyHandbrakesToCut

```csharp
private void ApplyHandbrakesToCut(IEnumerable<Car> cut, bool moved)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `carLoadPeriod` | `float` | public | - |
| `inputSpans` | `TrackSpan[]` | public | - |
| `outputSpans` | `TrackSpan[]` | public | - |
| `carLengthFeet` | `float` | public | - |
| `_graph` | `Graph` | private | - |
| `_trainController` | `TrainController` | private | - |
| `_routePoints` | `List<Vector3>` | private | `readonly` |
| `LastLoadedKey` | `string` | private | `const` |

