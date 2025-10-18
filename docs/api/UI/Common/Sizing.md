# Sizing Struct

**Namespace:** `UI.Common`
**Source:** `Window.cs`

## Declaration

```csharp
public readonly struct Sizing : IEquatable<Sizing>
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasUserResized` | `bool` | public | - |

## Methods

### SetPositionRestoring

```csharp
public void SetPositionRestoring(Vector2 position)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `resizer` | `PanelResizer` | private | - |
| `draggablePanel` | `DraggablePanel` | private | - |
| `DelegateRequestClose` | `Action` | public | - |
| `_resizable` | `bool` | private | - |
| `_hasRestoredSize` | `bool` | private | - |
| `_rectTransform` | `RectTransform` | private | - |

