# InteractiveBookRunner Class

**Namespace:** `Game.Scripting.Interactive`
**Source:** `InteractiveBookRunner.cs`

## Declaration

```csharp
public class InteractiveBookRunner : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CloseMessage` | `string` | public | - |

## Methods

### MarkComplete

```csharp
private void MarkComplete()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ui` | `IPageUI` | public | `readonly` |
| `properties` | `ScriptProperties` | public | - |
| `world` | `ScriptWorld` | public | - |
| `request_rerun` | `Action` | public | - |
| `mark_complete` | `Action` | public | - |
| `_basePath` | `string` | private | - |
| `_bookName` | `string` | private | - |
| `_bookFilename` | `string` | private | - |
| `_pageUI` | `IPageUI` | private | - |
| `_keyValueObject` | `IKeyValueObject` | private | - |
| `_script` | `ScriptManager` | private | - |
| `_lastModifiedTime` | `DateTime` | private | - |
| `_runClosure` | `Closure` | private | - |

