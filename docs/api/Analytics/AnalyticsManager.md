# AnalyticsManager Class

**Namespace:** `Analytics`
**Source:** `AnalyticsManager.cs`

## Declaration

```csharp
public class AnalyticsManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `AnalyticsManager` | public | `static` |

## Methods

### PostEvents

```csharp
private IEnumerator PostEvents(EventPartial[] events)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_coroutine` | `Coroutine` | private | - |
| `_queue` | `List<EventPartial>` | private | `readonly` |
| `_template` | `Event` | private | - |
| `ApiKey` | `string` | private | `const` |
| `Timestamp` | `long` | private | `static` |
| `AnalyticsEnabled` | `bool` | private | `static` |

