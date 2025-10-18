# Frame Struct

**Namespace:** `Track`
**Source:** `TurntableReceiver.cs`

## Declaration

```csharp
private struct Frame
```

## Methods

### UpdatePosition

```csharp
private void UpdatePosition()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Tick` | `long` | public | - |
| `Angle` | `float` | public | - |
| `Tick` | `long` | public | - |
| `Angle` | `float` | public | - |
| `turntableController` | `TurntableController` | public | - |
| `Delay` | `long` | public | `const` |
| `_frames` | `CircularBuffer<Frame>` | private | `readonly` |
| `displayTick` | `long` | private | - |

