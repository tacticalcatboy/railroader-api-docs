# UIPanel Class

**Namespace:** `UI.Builder`
**Source:** `UIPanel.cs`

## Declaration

```csharp
public class UIPanel : IDisposable
```

## Methods

### RebuildOnInterval

```csharp
public void RebuildOnInterval(float seconds)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_assets` | `UIBuilderAssets` | private | `readonly` |
| `_container` | `RectTransform` | private | `readonly` |
| `_buildClosure` | `Action<UIPanelBuilder>` | private | `readonly` |
| `_children` | `HashSet<UIPanel>` | private | `readonly` |
| `_parent` | `UIPanel` | private | - |
| `_id` | `int` | private | - |
| `_nextId` | `int` | private | `static` |
| `_registeredForEvents` | `bool` | private | - |
| `_keyChangeObservers` | `HashSet<IDisposable>` | private | `readonly` |
| `_timer` | `Timer` | private | - |

