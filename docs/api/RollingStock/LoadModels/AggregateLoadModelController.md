# AggregateLoadModelController Class

**Namespace:** `RollingStock.LoadModels`
**Source:** `AggregateLoadModelController.cs`

## Declaration

```csharp
public class AggregateLoadModelController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IdHashCode` | `int` | private | - |

## Methods

### TryGetMaterialDefinition

```csharp
private bool TryGetMaterialDefinition(IPrefabStore prefabStore, out TypedContainerItem<MaterialDefinition> materialDefinitionItem)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `atlasIndex` | `int` | public | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_observer` | `IDisposable` | private | - |
| `_slot` | `int` | private | - |
| `_loadIdentifier` | `string` | private | - |
| `_load` | `Load` | private | - |
| `_car` | `Car` | private | - |
| `_maxSize` | `Vector3` | private | - |
| `_currentLoadId` | `string` | private | - |
| `_materialLoadCancellationTokenSource` | `CancellationTokenSource` | private | - |
| `_loadReference` | `LoadedAssetReference<Material>` | private | - |
| `_meshGameObject` | `GameObject` | private | - |
| `_materialDefinition` | `MaterialDefinition` | private | - |
| `_warnedMissingMaterialDefinitionForLoadId` | `string` | private | - |
| `MaterialFieldAggregateModelLoadId` | `string` | private | `const` |
| `MaterialFieldAggregateModelBumps` | `string` | private | `const` |
| `LoadKey` | `string` | private | - |

