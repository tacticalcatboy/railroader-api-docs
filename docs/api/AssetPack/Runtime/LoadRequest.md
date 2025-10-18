# LoadRequest Class

**Namespace:** `AssetPack.Runtime`
**Source:** `AssetPackRuntimeStore.cs`

## Declaration

```csharp
private class LoadRequest
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Identifier` | `string` | public | - |

## Methods

### SaveContainer

```csharp
public void SaveContainer()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_container` | `Container` | private | - |
| `_loadAssetBundleTask` | `Task<AssetBundle>` | private | - |
| `_staticAssetBundle` | `AssetBundle` | private | - |
| `_disposed` | `bool` | private | - |
| `BasePath` | `string` | private | - |
| `AssetBundlePath` | `string` | private | - |
| `CatalogPath` | `string` | private | - |
| `DefinitionsPath` | `string` | private | - |

