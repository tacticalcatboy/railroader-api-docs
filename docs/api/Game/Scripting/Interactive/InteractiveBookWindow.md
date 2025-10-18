# InteractiveBookWindow Class

**Namespace:** `Game.Scripting.Interactive`
**Source:** `InteractiveBookWindow.cs`

## Declaration

```csharp
public class InteractiveBookWindow : MonoBehaviour, IProgrammaticWindow, IBuilderWindow, IPageUI
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsShown` | `bool` | public | - |

## Methods

### clear

```csharp
public void clear()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Text` | `string` | public | - |
| `Title` | `string` | public | - |
| `Message` | `string` | public | - |
| `Value` | `float` | public | - |
| `Style` | `GoalStyle` | public | - |
| `CustomDisplay` | `string` | public | - |
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `_runner` | `InteractiveBookRunner` | private | - |
| `_scrollViewRectTransform` | `RectTransform` | private | - |
| `_showReloadButton` | `bool` | private | - |
| `_keyValueObject` | `IKeyValueObject` | private | - |
| `_completeObserver` | `IDisposable` | private | - |
| `_pendingCloseRequest` | `bool` | private | - |
| `_arrowOverlayIds` | `List<int>` | private | `readonly` |
| `OnPlayerClosed` | `Action` | public | - |
| `_elements` | `List<object>` | private | `readonly` |
| `_navButtons` | `List<ElementButton>` | private | `readonly` |
| `WindowIdentifier` | `string` | public | - |
| `DefaultSize` | `Vector2Int` | public | - |
| `Shared` | `InteractiveBookWindow` | public | `static` |

