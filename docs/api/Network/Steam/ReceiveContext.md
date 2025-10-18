# ReceiveContext Class

**Namespace:** `Network.Steam`
**Source:** `ReceiveContext.cs`

## Declaration

```csharp
public class ReceiveContext
```

## Methods

### NetworkMessageFromPointer

```csharp
public INetworkMessage NetworkMessageFromPointer(IntPtr ptr, out HSteamNetConnection connection)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_gzipSourceStream` | `ArraySegmentReadStream` | private | `readonly` |
| `_gzipDestStream` | `WriteBufferStream` | private | `readonly` |

