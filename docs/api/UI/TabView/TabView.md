# TabView Class

**Namespace:** `UI.TabView`
**Source:** `TabView.cs`

## Declaration

```csharp
public class TabView : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Parent` | `UIPanel` | public | - |

## Methods

### IndexForTabId

```csharp
private int IndexForTabId(string tabId)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `togglePrefab` | `Toggle` | private | - |
| `buttons` | `RectTransform` | private | - |
| `content` | `RectTransform` | private | - |
| `assets` | `UIBuilderAssets` | public | - |
| `_tabIds` | `List<string>` | private | `readonly` |
| `_tabBuildClosures` | `List<Action<UIPanelBuilder>>` | private | `readonly` |
| `_toggles` | `List<Toggle>` | private | `readonly` |
| `_toggleGroup` | `ToggleGroup` | private | - |
| `_contentPanel` | `UIPanel` | private | - |

