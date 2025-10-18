# GirtPoint Struct

**Namespace:** `AutoTrestle`
**Source:** `AutoTrestle.cs`

## Declaration

```csharp
private struct GirtPoint
```

## Methods

### MakeCrossBeamCentered

```csharp
private void MakeCrossBeamCentered(Vector2 dimension, float length, Vector4 at)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `controlPoints` | `List<ControlPoint>` | public | - |
| `headStyle` | `EndStyle` | public | - |
| `tailStyle` | `EndStyle` | public | - |
| `_hideFlags` | `HideFlags` | private | `const` |
| `_generateTask` | `CoroutineTask` | private | - |
| `_hasGenerated` | `bool` | private | - |
| `_meshRenderers` | `List<MeshRenderer>` | private | `readonly` |
| `inToM` | `float` | private | `const` |
| `ftToM` | `float` | private | `const` |

