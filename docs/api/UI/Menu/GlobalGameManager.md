# GlobalGameManager Class

**Namespace:** `UI.Menu`
**Source:** `GlobalGameManager.cs`

## Declaration

```csharp
public class GlobalGameManager : ScriptableObject
```

## Methods

### _ReturnToMainMenu

```csharp
private await _ReturnToMainMenu()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Descriptors` | `List<SceneDescriptor>` | public | `readonly` |
| `Active` | `SceneDescriptor` | public | `readonly` |
| `_persistentLoader` | `PersistentLoader` | private | - |
| `_state` | `State` | private | - |
| `_loadedMapSceneDescriptors` | `List<SceneDescriptor>` | private | - |

