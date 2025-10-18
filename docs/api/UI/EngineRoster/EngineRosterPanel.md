# EngineRosterPanel Class

**Namespace:** `UI.EngineRoster`
**Source:** `EngineRosterPanel.cs`

## Declaration

```csharp
public class EngineRosterPanel : MonoBehaviour
```

## Methods

### ToggleFavorite

```csharp
public void ToggleFavorite(BaseLocomotive engine)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `emptyStateRect` | `RectTransform` | private | - |
| `_window` | `Window` | private | - |
| `_cachedFavorites` | `HashSet<string>` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_lastHash` | `int` | private | - |
| `PropertiesManager` | `PlayerPropertiesManager` | private | `static` |
| `Shared` | `EngineRosterPanel` | public | `static` |

