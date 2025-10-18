# CatalogEntry Class

**Namespace:** `UI.Equipment`
**Source:** `EquipmentWindow.cs`

## Declaration

```csharp
private class CatalogEntry
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### BuildDetails

```csharp
private void BuildDetails(UIPanelBuilder builder, string identifier, ObjectMetadata metadata, DieselLocomotiveDefinition def)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CarDefinitionInfo` | `TypedContainerItem<CarDefinition>` | public | - |
| `_window` | `Window` | private | - |
| `_instance` | `EquipmentWindow` | private | `static` |
| `_panel` | `UIPanel` | private | - |
| `_catalog` | `List<CatalogEntry>` | private | `readonly` |
| `_selectedItem` | `UIState<string>` | private | `readonly` |
| `_quantityId` | `string` | private | - |
| `_quantity` | `int` | private | - |
| `Shared` | `EquipmentWindow` | public | `static` |
| `PrefabStore` | `IPrefabStore` | private | - |

