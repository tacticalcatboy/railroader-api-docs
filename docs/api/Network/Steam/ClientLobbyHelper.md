# ClientLobbyHelper Class

**Namespace:** `Network.Steam`
**Source:** `ClientLobbyHelper.cs`

## Declaration

```csharp
public class ClientLobbyHelper : IDisposable
```

## Methods

### HandleLobbyGameCreated

```csharp
private void HandleLobbyGameCreated(LobbyGameCreated_t arg)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_lobbies` | `LobbyData[]` | private | - |
| `_joinedLobby` | `LobbyData` | private | - |
| `_taskCompletionSourceGameCreated` | `TaskCompletionSource<VoidResult>` | private | - |

