# LocalGameClient Class

**Namespace:** `Network.Client`
**Source:** `LocalGameClient.cs`

## Declaration

```csharp
public class LocalGameClient : GameClient, IServerManager
```

## Methods

### DropClient

```csharp
public void DropClient(ClientId clientId, int steamworksReasonCode, string debugReason)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HostManager` | `HostManager` | private | - |
| `_connected` | `bool` | private | - |
| `_pendingReceive` | `List<INetworkMessage>` | private | `readonly` |
| `_buffer` | `NetworkBufferWriter` | private | `readonly` |
| `ClientId` | `ClientId` | private | `static` |

