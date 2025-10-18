# StationWindow Class

**Namespace:** `UI.StationWindow`
**Source:** `StationWindow.cs`

## Declaration

```csharp
public class StationWindow : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `BuilderAssets` | `UIBuilderAssets` | public | - |

## Methods

### BuildFreightTab

```csharp
private void BuildFreightTab(UIPanelBuilder builder, List<Area> areas, OpsCarList freightCars)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TabIdPassenger` | `string` | private | `const` |
| `TabIdFreight` | `string` | private | `const` |
| `_window` | `Window` | private | - |
| `_instance` | `StationWindow` | private | `static` |
| `_selectedTabState` | `UIState<string>` | private | `readonly` |
| `_panel` | `UIPanel` | private | - |
| `HstackSpacing` | `int` | private | `const` |
| `ColumnWidthCar` | `int` | private | `const` |
| `ColumnWidthLocation` | `int` | private | `const` |
| `ColumnWidthToggle` | `int` | private | `const` |
| `Shared` | `StationWindow` | public | `static` |

