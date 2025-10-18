# TextLinkReceiver Class

**Namespace:** `UI`
**Source:** `TextLinkReceiver.cs`

## Declaration

```csharp
public class TextLinkReceiver : MonoBehaviour, IPointerClickHandler, IEventSystemHandler
```

## Methods

### OnPointerClick

```csharp
public void OnPointerClick(PointerEventData eventData)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_text` | `TMP_Text` | private | - |
| `OnLinkClicked` | `Action<string>` | public | - |

