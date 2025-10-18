# CircularBuffer Class

**Namespace:** `Helpers`
**Source:** `CircularBuffer.cs`

## Declaration

```csharp
public class CircularBuffer : IEnumerable<T>, IEnumerable
```

## Methods

### Clear

```csharp
public void Clear()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_buffer` | `T[]` | private | `readonly` |
| `_head` | `int` | private | - |
| `_tail` | `int` | private | - |
| `_length` | `int` | private | - |
| `_bufferSize` | `int` | private | `readonly` |
| `_lock` | `object` | private | `readonly` |
| `IsEmpty` | `bool` | public | - |
| `IsFull` | `bool` | public | - |
| `Length` | `int` | public | - |
| `Capacity` | `int` | public | - |

