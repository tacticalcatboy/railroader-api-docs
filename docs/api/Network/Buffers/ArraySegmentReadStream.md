# ArraySegmentReadStream Class

**Namespace:** `Network.Buffers`
**Source:** `ArraySegmentReadStream.cs`

## Declaration

```csharp
public class ArraySegmentReadStream : Stream
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
| `_arraySegment` | `ArraySegment<byte>` | private | - |

