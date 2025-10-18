# SceneDescriptor Struct

**Namespace:** `UI.Menu`
**Source:** `SceneDescriptor.cs`

## Declaration

```csharp
public readonly struct SceneDescriptor
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Scene` | `Scene` | public | - |

## Methods

### UnloadAsync

```csharp
public AsyncOperation UnloadAsync()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_path` | `string` | private | `readonly` |
| `_buildIndex` | `int` | private | `readonly` |
| `MainMenu` | `SceneDescriptor` | public | `static` |
| `GameUI` | `SceneDescriptor` | public | `static` |
| `PersistentLoader` | `SceneDescriptor` | public | `static` |
| `BushnellWhittier` | `SceneDescriptor` | public | `static` |
| `EnvironmentEnviro` | `SceneDescriptor` | public | `static` |
| `Editor` | `SceneDescriptor` | public | `static` |
| `Tests` | `SceneDescriptor` | public | `static` |
| `IsLoaded` | `bool` | public | - |
| `UsePath` | `bool` | private | - |

