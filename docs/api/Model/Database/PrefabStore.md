# PrefabStore Class

**Namespace:** `Model.Database`
**Source:** `PrefabStore.cs`

## Declaration

```csharp
public class PrefabStore : IDisposable, IPrefabStore
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `AllCarDefinitionInfos` | `IEnumerable<TypedContainerItem<CarDefinition>>` | public | - |

## Methods

### AssetPackIdentifierContainingDefinition

```csharp
public string AssetPackIdentifierContainingDefinition(string definitionIdentifier)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_stores` | `List<AssetPackRuntimeStore>` | private | `readonly` |
| `_truckReferences` | `HashSet<LoadedAssetReference<GameObject>>` | private | `readonly` |
| `ExternalStores` | `IEnumerable<AssetPackRuntimeStore>` | public | - |

