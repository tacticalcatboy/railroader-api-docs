# NoticeManager Class

**Namespace:** `Game.Notices`
**Source:** `NoticeManager.cs`

## Declaration

```csharp
public class NoticeManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `NoticeManager` | public | `static` |

## Methods

### PostEphemeralLocal

```csharp
public void PostEphemeralLocal(EntityReference entity, string contextualKey, string content)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Row` | `NoticeRow` | public | - |
| `Content` | `string` | public | - |
| `rowTemplate` | `NoticeRow` | private | - |
| `rowContainer` | `RectTransform` | private | - |
| `_shared` | `NoticeManager` | private | `static` |

