# SendContext Class

**Namespace:** `Network.Steam`
**Source:** `SendContext.cs`

## Declaration

```csharp
public class SendContext : IDisposable
```

## Methods

### Send

```csharp
public bool Send(INetworkMessage networkMessage)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Connection` | `HSteamNetConnection` | public | - |
| `Result` | `EResult` | public | - |
| `_bufferWriter` | `NetworkBufferWriter` | private | `readonly` |
| `_recipients` | `List<Recipient>` | private | `readonly` |
| `_gzipMemoryStream` | `WriteBufferStream` | private | - |

