# WhistleController Class

**Namespace:** `RollingStock.Steam`
**Source:** `WhistleController.cs`

## Declaration

```csharp
public class WhistleController : MonoBehaviour
```

## Methods

### Configure

```csharp
public void Configure(WhistleComponent whistleComponent)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `visualEffect` | `VisualEffect` | public | - |
| `whistlePlayer` | `WhistlePlayer` | public | - |
| `_whistleModel` | `GameObject` | private | - |
| `_modelLoadReference` | `LoadedAssetReference<GameObject>` | private | - |
| `_audioLoadReference` | `LoadedAssetReference<AudioClip>` | private | - |
| `_loadCancellationTokenSource` | `CancellationTokenSource` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_customizationObserver` | `IDisposable` | private | - |
| `EffectWrapper` | `SmokeEffectWrapper` | public | - |

