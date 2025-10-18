# SteamLocomotive Class

**Namespace:** `Model`
**Source:** `SteamLocomotive.cs`

## Declaration

```csharp
public class SteamLocomotive : BaseLocomotive
```

## Methods

### FuelCar

```csharp
internal Car FuelCar()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_wheelAnimator` | `SteamLocomotiveWheelAnimator` | private | - |
| `engine` | `SteamEngine` | public | - |
| `hasTender` | `bool` | public | - |
| `_chuffParticles` | `SteamChuffParticleController` | private | - |
| `_chuffAudio` | `IChuffProvider` | private | - |
| `_subcomponents` | `List<ISteamLocomotiveSubcomponent>` | private | `readonly` |
| `_hasSetSlots` | `bool` | private | - |
| `_coalSlot` | `int` | private | - |
| `_waterSlot` | `int` | private | - |
| `ReverserCenteredThreshold` | `float` | private | `const` |
| `_cutoffSettings` | `float[]` | private | - |
| `LocoDefinition` | `SteamLocomotiveDefinition` | public | - |

