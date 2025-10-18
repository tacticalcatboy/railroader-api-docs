# DieselLocomotive Class

**Namespace:** `Model`
**Source:** `DieselLocomotive.cs`

## Declaration

```csharp
public class DieselLocomotive : BaseLocomotive
```

## Methods

### CreateLocomotiveControl

```csharp
protected override LocomotiveControlAdapter CreateLocomotiveControl()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `primeMover` | `PrimeMover` | public | - |
| `_primeMoverAudioPlayer` | `IPrimeMoverAudioPlayer` | private | - |
| `_particleControllers` | `List<DieselExhaustParticleController>` | private | - |
| `LocoDefinition` | `DieselLocomotiveDefinition` | private | - |

