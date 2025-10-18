# Multiplayer Class

**Namespace:** `Network`
**Source:** `Multiplayer.cs`

## Declaration

```csharp
public static class Multiplayer
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Host` | `HostManager` | private | `static` |

## Methods

### OnClientDisconnect

```csharp
private static void OnClientDisconnect()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_serverGameObject` | `GameObject` | private | `static` |
| `_clientGameObject` | `GameObject` | private | `static` |
| `_clientLobbyHelper` | `ClientLobbyHelper` | private | `static` |
| `_serverLobbyHelper` | `ServerLobbyHelper` | private | `static` |
| `_steamServer` | `SteamServer` | private | `static` |
| `IsClientActive` | `bool` | public | `static` |
| `MySteamId` | `ulong` | public | `static` |
| `ClientLobbyHelper` | `ClientLobbyHelper` | public | `static` |

