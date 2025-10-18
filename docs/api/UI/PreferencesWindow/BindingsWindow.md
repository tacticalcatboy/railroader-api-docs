# BindingsWindow Class

**Namespace:** `UI.PreferencesWindow`
**Source:** `BindingsWindow.cs`

## Declaration

```csharp
public class BindingsWindow : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### DidRebind

```csharp
private void DidRebind()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_instance` | `BindingsWindow` | private | `static` |
| `_panel` | `UIPanel` | private | - |
| `_selectedTabState` | `UIState<string>` | private | `readonly` |
| `_conflicts` | `HashSet<InputAction>` | private | - |
| `_builder` | `UIPanelBuilder` | private | - |
| `Instance` | `BindingsWindow` | private | `static` |
| `CanShow` | `bool` | public | `static` |

