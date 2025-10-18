# ScriptTestsWindow Class

**Namespace:** `Game.Scripting.Testing`
**Source:** `ScriptTestsWindow.cs`

## Declaration

```csharp
public class ScriptTestsWindow : MonoBehaviour, IProgrammaticWindow, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### Reload

```csharp
private void Reload()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `_runner` | `ScriptTestRunner` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_refreshCoroutine` | `Coroutine` | private | - |
| `WindowIdentifier` | `string` | public | - |
| `DefaultSize` | `Vector2Int` | public | - |
| `Shared` | `ScriptTestsWindow` | public | `static` |

