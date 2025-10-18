# ConnectionInfo Struct

**Namespace:** `Network`
**Source:** `ConnectionInfo.cs`

## Declaration

```csharp
public struct ConnectionInfo
```

## Methods

### Singleplayer

```csharp
public static ConnectionInfo Singleplayer(string username, Snapshot.CharacterCustomization customization)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Mode` | `ConnectionMode` | public | `readonly` |
| `GameServerId` | `CSteamID` | public | `readonly` |
| `Username` | `string` | public | `readonly` |
| `Password` | `string` | public | - |
| `IsSingleplayer` | `bool` | public | - |
| `IsMultiplayerServer` | `bool` | public | - |
| `IsMultiplayerClient` | `bool` | public | - |

