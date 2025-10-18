# RawNetworkMessage Struct

**Namespace:** `Network.Steam`
**Source:** `RawNetworkMessage.cs`

## Declaration

```csharp
internal readonly struct RawNetworkMessage
```

## Methods

### FromPointer

```csharp
public static RawNetworkMessage FromPointer(IntPtr ptr)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Connection` | `HSteamNetConnection` | public | `readonly` |
| `Identity` | `SteamNetworkingIdentity` | public | `readonly` |
| `DataPtr` | `IntPtr` | public | `readonly` |
| `DataLength` | `int` | public | `readonly` |
| `TimeReceived` | `SteamNetworkingMicroseconds` | public | `readonly` |
| `MessageNumber` | `long` | public | `readonly` |
| `Channel` | `int` | public | `readonly` |

