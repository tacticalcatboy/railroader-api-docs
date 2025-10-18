# MultiplayerJoinMenu Class

**Namespace:** `UI.Menu`
**Source:** `MultiplayerJoinMenu.cs`

## Declaration

```csharp
public class MultiplayerJoinMenu : MonoBehaviour, INavigationView
```

## Methods

### WillAppear

```csharp
public void WillAppear()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Username` | `string` | public | - |
| `SteamLobbyId` | `CSteamID` | public | - |
| `statusLabel` | `TMP_Text` | private | - |
| `refreshButton` | `Button` | private | - |
| `backButton` | `Button` | private | - |
| `usernameField` | `TMP_InputField` | private | - |
| `filterField` | `TMP_InputField` | private | - |
| `OnJoin` | `Action<JoinInfo>` | public | - |
| `_clientLobbyHelper` | `ClientLobbyHelper` | private | - |
| `_lobbies` | `IReadOnlyCollection<LobbyData>` | private | - |
| `RectTransform` | `RectTransform` | public | - |

