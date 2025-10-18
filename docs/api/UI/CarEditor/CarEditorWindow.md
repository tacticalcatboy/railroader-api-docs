# CarEditorWindow Class

**Namespace:** `UI.CarEditor`
**Source:** `CarEditorWindow.cs`

## Declaration

```csharp
public class CarEditorWindow : MonoBehaviour
```

## Methods

### DisplayNameForComponentType

```csharp
private static string DisplayNameForComponentType(Type type)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `primary` | `ObjectEditorPrimaryPanel` | private | - |
| `secondary` | `ObjectEditorSecondaryPanel` | private | - |
| `applyButton` | `Button` | private | - |
| `removeComponentButton` | `Button` | private | - |
| `duplicateComponentButton` | `Button` | private | - |
| `addComponentDropdown` | `TMP_Dropdown` | private | - |
| `_window` | `Window` | private | - |
| `_store` | `AssetPackRuntimeStore` | private | - |
| `_item` | `ContainerItem` | private | - |
| `_carId` | `string` | private | - |
| `_refreshCoroutine` | `Coroutine` | private | - |
| `_componentGameObject` | `GameObject` | private | - |
| `_componentEditor` | `ComponentEditor` | private | - |
| `_definitionEditor` | `DefinitionEditor` | private | - |
| `_addComponentOptions` | `List<Type>` | private | `readonly` |
| `_selectedObject` | `object` | private | - |
| `_onChanged` | `Action` | private | - |
| `Instance` | `CarEditorWindow` | private | `static` |
| `IsShown` | `bool` | public | `static` |

