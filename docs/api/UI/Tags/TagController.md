# TagController Class

**Namespace:** `UI.Tags`
**Source:** `TagController.cs`

## Declaration

```csharp
public class TagController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `TagController` | public | `static` |

## Methods

### Tick

```csharp
private IEnumerator Tick(bool updateAllImmediately)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_shared` | `TagController` | private | `static` |
| `tagCalloutPrefab` | `TagCallout` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_pool` | `Queue<TagCallout>` | private | `readonly` |
| `TagsVisible` | `bool` | public | - |
| `TrainController` | `TrainController` | private | - |

