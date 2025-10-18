# WriteBufferStream Class

**Namespace:** `Network.Buffers`
**Source:** `WriteBufferStream.cs`

## Declaration

```csharp
public class WriteBufferStream : Stream
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `long` | public | `override` |

## Methods

### Seek

```csharp
public override long Seek(long offset, SeekOrigin origin)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_buffer` | `byte[]` | private | - |
| `_position` | `int` | private | - |
| `ArraySegment` | `ArraySegment<byte>` | public | - |

