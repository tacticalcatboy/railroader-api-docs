# NetworkBufferWriter Class

**Namespace:** `Network.Buffers`
**Source:** `NetworkBufferWriter.cs`

## Declaration

```csharp
public class NetworkBufferWriter : IBufferWriter<byte>, IDisposable
```

## Methods

### GetSpan

```csharp
public Span<byte> GetSpan(int sizeHint = 0)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MinimumBufferSize` | `int` | private | `const` |
| `_rentedBuffer` | `byte[]` | private | - |
| `_written` | `int` | private | - |
| `Array` | `byte[]` | public | - |
| `ArrayLength` | `int` | public | - |

