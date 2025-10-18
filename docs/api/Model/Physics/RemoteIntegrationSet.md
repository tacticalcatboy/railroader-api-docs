# RemoteIntegrationSet Class

**Namespace:** `Model.Physics`
**Source:** `RemoteIntegrationSet.cs`

## Declaration

```csharp
public class RemoteIntegrationSet : IntegrationSet
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DisplayTick` | `long` | private | - |

## Methods

### AddFrame

```csharp
private void AddFrame(Frame frame)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Tick` | `long` | public | - |
| `Locations` | `Location[]` | public | - |
| `Velocities` | `float[]` | public | - |
| `_frames` | `List<Frame>` | private | `readonly` |
| `_extrapolated` | `Frame` | private | - |

