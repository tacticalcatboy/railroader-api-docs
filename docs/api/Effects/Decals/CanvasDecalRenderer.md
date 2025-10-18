# CanvasDecalRenderer Class

**Namespace:** `Effects.Decals`
**Source:** `CanvasDecalRenderer.cs`

## Declaration

```csharp
public class CanvasDecalRenderer : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `CanvasDecalRenderer` | public | `static` |

## Methods

### Render

```csharp
public Task<CanvasDecal> Render(Vector2 decalProjectorSize, string template, string text, CancellationToken cancellationToken)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ReferenceCount` | `int` | public | - |
| `DecalProjectorSize` | `Vector2` | public | - |
| `Template` | `string` | public | - |
| `Text` | `string` | public | - |
| `TaskCompletionSource` | `TaskCompletionSource<CanvasDecal>` | public | - |
| `CancellationToken` | `CancellationToken` | public | - |
| `canvasCamera` | `Camera` | public | - |
| `container` | `RectTransform` | public | - |
| `pixelsPerMeterLarge` | `int` | public | - |
| `pixelsPerMeterSmall` | `int` | public | - |
| `referenceMaterial` | `Material` | public | - |
| `StandardContainerWidth` | `float` | private | `const` |
| `_coroutine` | `Coroutine` | private | - |
| `_queue` | `Queue<Request>` | private | - |
| `_instance` | `CanvasDecalRenderer` | private | `static` |

