# UIPanelBuilder Struct

**Namespace:** `UI.Builder`
**Source:** `UIPanelBuilder.cs`

## Declaration

```csharp
public struct UIPanelBuilder
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Spacing` | `float` | public | - |

## Methods

### HStack

```csharp
public RectTransform HStack(Action<UIPanelBuilder> closure, float spacing = 4f)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Identifier` | `string` | public | `readonly` |
| `Value` | `TValue` | public | `readonly` |
| `_assets` | `UIBuilderAssets` | private | `readonly` |
| `_container` | `RectTransform` | private | `readonly` |
| `_panel` | `UIPanel` | private | `readonly` |
| `_rebindOverlay` | `GameObject` | private | `static` |

