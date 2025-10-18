# ModelHierarchyEntry Struct

**Namespace:** `UI.CarEditor`
**Source:** `ObjectEditorSecondaryPanel.cs`

## Declaration

```csharp
public struct ModelHierarchyEntry
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Path` | `string[]` | public | - |

## Methods

### CreateTextFieldCell

```csharp
private EditorTextFieldCell CreateTextFieldCell(RectTransform parent)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `scrollContent` | `RectTransform` | private | - |
| `headerCellPrototype` | `EditorHeaderCell` | private | - |
| `textFieldCellPrototype` | `EditorTextFieldCell` | private | - |
| `floatCellPrototype` | `EditorFloatCell` | private | - |
| `vector3CellPrototype` | `EditorVector3Cell` | private | - |
| `arrayCellPrototype` | `EditorArrayCell` | private | - |
| `nestedCellPrototype` | `EditorNestedCell` | private | - |
| `dropdownCellPrototype` | `EditorDropdownCell` | private | - |
| `checkboxCellPrototype` | `EditorCheckboxCell` | private | - |
| `_object` | `object` | private | - |
| `_requestRefresh` | `Action` | private | - |
| `_mapNames` | `ModelMapNames` | private | - |
| `_modelHierarchy` | `List<ModelHierarchyEntry>` | private | - |
| `_titleCell` | `EditorHeaderCell` | private | - |

