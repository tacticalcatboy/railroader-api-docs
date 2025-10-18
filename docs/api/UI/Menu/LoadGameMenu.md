# LoadGameMenu Class

**Namespace:** `UI.Menu`
**Source:** `LoadGameMenu.cs`

## Declaration

```csharp
public class LoadGameMenu : MonoBehaviour, INavigationView
```

## Methods

### WillAppear

```csharp
public void WillAppear()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `titleLabel` | `TMP_Text` | private | - |
| `rowTemplate` | `LoadGameRow` | private | - |
| `scrollViewContent` | `RectTransform` | private | - |
| `toggleGroup` | `ToggleGroup` | private | - |
| `newButton` | `Button` | private | - |
| `startButton` | `Button` | private | - |
| `backButton` | `Button` | private | - |
| `OnNewGame` | `Action` | public | - |
| `OnLoadGame` | `Action<string>` | public | - |
| `RectTransform` | `RectTransform` | public | - |

