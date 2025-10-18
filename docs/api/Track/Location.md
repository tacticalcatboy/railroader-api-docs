# Location Struct

**Namespace:** `Track`
**Source:** `Location.cs`

## Declaration

```csharp
public readonly struct Location : IEquatable<Location>
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `NodeString` | `string` | public | - |

## Methods

### Serializable

```csharp
public SerializableLocation Serializable()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `segment` | `TrackSegment` | public | `readonly` |
| `distance` | `float` | public | `readonly` |
| `Distance` | `float` | public | - |
| `EndIsA` | `bool` | public | - |
| `Invalid` | `Location` | public | `static` |
| `operator` | `bool` | public | `static` |

