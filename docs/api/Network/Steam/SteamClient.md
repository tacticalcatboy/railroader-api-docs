# SteamClient Class

**Namespace:** `Network.Steam`
**Source:** `SteamClient.cs`

## Declaration

```csharp
public class SteamClient : GameClient
```

## Methods

### Disconnect

```csharp
public override void Disconnect()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_gameServerId` | `CSteamID` | private | - |
| `_connection` | `HSteamNetConnection` | private | - |
| `_callbackConnectionStatusChanged` | `Callback<SteamNetConnectionStatusChangedCallback_t>` | private | - |
| `_isConnectedOrConnecting` | `bool` | private | - |
| `_receivedMessagePointers` | `IntPtr[]` | private | `readonly` |
| `_sendContext` | `SendContext` | private | `readonly` |
| `_receiveContext` | `ReceiveContext` | private | `readonly` |

