# LobbyRow Class

**Namespace:** `UI.Menu`
**Source:** `LobbyRow.cs`

## Declaration

```csharp
public class LobbyRow : MonoBehaviour, ILazyScrollListCell
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ListIndex` | `int` | public | - |

## Methods

### Configure

```csharp
private void Configure(string lobbyName, string version, string countText, bool allowNewPlayers, bool passworded)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LobbyName` | `string` | public | `readonly` |
| `Version` | `string` | public | `readonly` |
| `CountText` | `string` | public | `readonly` |
| `AllowNewPlayers` | `bool` | public | `readonly` |
| `HasPassword` | `bool` | public | `readonly` |
| `Lobby` | `LobbyData` | public | `readonly` |
| `OnJoin` | `Action<LobbyData>` | public | `readonly` |
| `titleLabel` | `TMP_Text` | private | - |
| `countLabel` | `TMP_Text` | private | - |
| `flagsLabel` | `TMP_Text` | private | - |
| `joinButton` | `Button` | private | - |
| `_info` | `Info` | private | - |
| `RectTransform` | `RectTransform` | public | - |

