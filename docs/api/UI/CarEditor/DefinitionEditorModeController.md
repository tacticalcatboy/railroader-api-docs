# DefinitionEditorModeController Class

**Namespace:** `UI.CarEditor`
**Source:** `DefinitionEditorModeController.cs`

## Declaration

```csharp
public class DefinitionEditorModeController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsEditing` | `bool` | public | `static` |

## Methods

### EditItemCar

```csharp
private void EditItemCar(ContainerItem item, CarDefinition carDefinition, out string carId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `rldApp` | `RLDApp` | private | - |
| `rtFocusCamera` | `RTFocusCamera` | private | - |
| `_store` | `AssetPackRuntimeStore` | private | - |
| `_selectedItem` | `ContainerItem` | private | - |
| `_filterText` | `string` | private | - |
| `_newIdentifier` | `string` | private | - |
| `_lastCarDiagnostics` | `string` | private | - |
| `_guiBackgroundTexture` | `Texture2D` | private | `static` |
| `TrainController` | `TrainController` | private | - |

