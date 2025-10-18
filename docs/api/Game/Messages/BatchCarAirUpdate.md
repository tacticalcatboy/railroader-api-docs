# BatchCarAirUpdate Struct

**Namespace:** `Game.Messages`
**Source:** `BatchCarAirUpdate.cs`

## Declaration

```csharp
public struct BatchCarAirUpdate : IGameMessage
```

## Methods

### ByteToValue

```csharp
public static float ByteToValue(byte value)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Tick` | `long` | public | `readonly` |
| `CarIds` | `string[]` | public | `readonly` |
| `BrakeLineValues` | `byte[]` | public | `readonly` |
| `BrakeReservoirValues` | `byte[]` | public | `readonly` |
| `BrakeCylinderValues` | `byte[]` | public | `readonly` |
| `MaxValue` | `float` | private | `const` |

