# ScriptManager Class

**Namespace:** `Game.Scripting`
**Source:** `ScriptManager.cs`

## Declaration

```csharp
public class ScriptManager : IDisposable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CurrentScript` | `Script` | internal | `static` |

## Methods

### Reset

```csharp
private void Reset()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Message` | `string` | public | `readonly` |
| `DecoratedMessage` | `string` | public | `readonly` |
| `_script` | `Script` | private | - |
| `_player` | `IPlayer` | private | `readonly` |
| `_hostComponent` | `MonoBehaviour` | private | `readonly` |
| `_scriptLoader` | `ScriptLoaderBase` | private | `readonly` |
| `_currentScript` | `Script` | private | `static` |
| `_initialized` | `bool` | private | `static` |
| `BuiltInModulesPath` | `string` | public | `static` |

