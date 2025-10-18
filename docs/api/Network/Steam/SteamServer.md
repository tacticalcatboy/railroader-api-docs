# SteamServer Class

**Namespace:** `Network.Steam`
**Source:** `SteamServer.cs`

## Declaration

```csharp
public class SteamServer : MonoBehaviour, IServerManager
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `RemotePlayerSteamId` | `ulong` | public | - |

## Methods

### DispatchClientDidConnect

```csharp
private void DispatchClientDidConnect(Client client)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Delegate` | `IServerDelegate` | public | - |
| `_callbackConnectionStatusChanged` | `Callback<SteamNetConnectionStatusChangedCallback_t>` | private | - |
| `_listenSocket` | `HSteamListenSocket` | private | - |
| `_pollGroup` | `HSteamNetPollGroup` | private | - |
| `_receivedMessagePointers` | `IntPtr[]` | private | - |
| `_receiveContext` | `ReceiveContext` | private | `readonly` |
| `_bufferWriter` | `NetworkBufferWriter` | private | `readonly` |

