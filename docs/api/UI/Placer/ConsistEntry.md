# ConsistEntry Struct

**Namespace:** `UI.Placer`
**Source:** `PlacerWindow.cs`

## Declaration

```csharp
private struct ConsistEntry
```

## Methods

### InstantiateCell

```csharp
private void InstantiateCell(ConsistEntry entry, int index)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DefinitionInfo` | `TypedContainerItem<CarDefinition>` | public | - |
| `Definition` | `CarDefinition` | public | - |
| `libraryScrollContent` | `RectTransform` | public | - |
| `libraryRowTemplate` | `LibraryRow` | public | - |
| `consistScrollContent` | `RectTransform` | public | - |
| `consistRowTemplate` | `LibraryRow` | public | - |
| `placeButton` | `Button` | public | - |
| `summaryLabel` | `TMP_Text` | public | - |
| `filterToggles` | `Toggle[]` | public | - |
| `_window` | `Window` | private | - |
| `_consist` | `List<ConsistEntry>` | private | `readonly` |
| `_filter` | `Filter` | private | - |
| `PrefabStore` | `IPrefabStore` | private | - |
| `instance` | `PlacerWindow` | private | `static` |

