# Routing Struct

**Namespace:** `Game`
**Source:** `HostManager.cs`

## Declaration

```csharp
private readonly struct Routing
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MySteamId` | `ulong` | private | - |

## Methods

### SendPlayerRecords

```csharp
private void SendPlayerRecords()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ClientId` | `ClientId` | public | `readonly` |
| `Server` | `IServerManager` | public | `readonly` |
| `PlayerId` | `PlayerId` | public | - |
| `PlayerId` | `PlayerId` | public | `readonly` |
| `Name` | `string` | public | - |
| `SteamId` | `ulong` | public | `readonly` |
| `SteamName` | `string` | public | `readonly` |
| `route` | `Route` | public | `readonly` |
| `id` | `string` | public | `readonly` |
| `_pendingRequestActive` | `HashSet<ClientId>` | private | `readonly` |
| `_hasLoadedSnapshot` | `bool` | private | - |
| `_sendToClients` | `List<Client>` | private | `readonly` |
| `_sendContext` | `SendContext` | private | `readonly` |
| `_cachedUserData` | `UserData` | private | - |
| `_cachedHostPlayerId` | `PlayerId` | private | - |
| `_snapshot` | `Snapshot` | private | - |
| `_queueForBannedDisconnect` | `HashSet<Client>` | private | `readonly` |
| `_deepCopyBuffer` | `NetworkBufferWriter` | private | `readonly` |
| `HostOnlyKeyPrefix` | `string` | public | `const` |
| `NumPassengersOnline` | `int` | private | - |

