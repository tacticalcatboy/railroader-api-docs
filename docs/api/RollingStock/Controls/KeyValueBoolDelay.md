# KeyValueBoolDelay Class

**Namespace:** `RollingStock.Controls`
**Source:** `KeyValueBoolDelay.cs`

## Declaration

```csharp
public class KeyValueBoolDelay : MonoBehaviour
```

## Methods

### PropertyChanged

```csharp
private void PropertyChanged(Value value)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `sourceKey` | `string` | public | - |
| `targetKey` | `string` | public | - |
| `onDelay` | `float` | public | - |
| `offDelay` | `float` | public | - |
| `_observer` | `IDisposable` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_isInitial` | `bool` | private | - |
| `_coroutine` | `Coroutine` | private | - |

