# CarLoadModelController Class

**Namespace:** `RollingStock`
**Source:** `CarLoadModelController.cs`

## Declaration

```csharp
public class CarLoadModelController : MonoBehaviour
```

## Methods

### LoadMatches

```csharp
private bool LoadMatches(string loadId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_observer` | `IDisposable` | private | - |
| `_slot` | `int` | private | - |
| `_loadIdentifier` | `string` | private | - |
| `_load` | `Load` | private | - |
| `_car` | `Car` | private | - |
| `_instancePositions` | `List<PositionRotationScale>` | private | - |
| `_instanceGameObjects` | `List<GameObject>` | private | `readonly` |
| `_modelLoadCancellationTokenSource` | `CancellationTokenSource` | private | - |
| `_modelLoadReferences` | `List<LoadedAssetReference<GameObject>>` | private | `readonly` |
| `LoadKey` | `string` | private | - |

