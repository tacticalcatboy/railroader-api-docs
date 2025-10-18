# ContextMenu Class

**Namespace:** `UI.ContextMenu`
**Source:** `ContextMenu.cs`

## Declaration

```csharp
public class ContextMenu : MonoBehaviour, ICancelHandler, IEventSystemHandler
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `ContextMenu` | public | `static` |

## Methods

### Clear

```csharp
public void Clear()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `contentRectTransform` | `RectTransform` | protected | - |
| `itemPrefab` | `ContextMenuItem` | private | - |
| `dividerPrefab` | `RectTransform` | private | - |
| `radius` | `float` | private | - |
| `centerRectTransform` | `RectTransform` | private | - |
| `centerCanvasGroup` | `CanvasGroup` | private | - |
| `centerLabel` | `TMP_Text` | private | - |
| `showTime` | `float` | private | - |
| `hideTime` | `float` | private | - |
| `_blocker` | `GameObject` | private | - |
| `_hasSetupTemplate` | `bool` | private | - |
| `HighSortingLayer` | `int` | private | `const` |
| `NumZones` | `int` | private | `const` |
| `_quadrants` | `List<List<ContextMenuItem>>` | private | `readonly` |
| `_dividers` | `List<RectTransform>` | private | `readonly` |
| `_hideCoroutine` | `Coroutine` | private | - |
| `_shared` | `ContextMenu` | private | `static` |
| `ContentGameObject` | `GameObject` | private | - |

