# CarInspector Class

**Namespace:** `UI.CarInspector`
**Source:** `CarInspector.cs`

## Declaration

```csharp
public class CarInspector : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CanSetWaybill` | `bool` | private | - |

## Methods

### AddDropdownItem

```csharp
private void AddDropdownItem(IndustryComponent ic, Area area)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_car` | `Car` | private | - |
| `_trainCrews` | `List<TrainCrew>` | private | - |
| `_instance` | `CarInspector` | private | `static` |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_selectedTabState` | `UIState<string>` | private | `readonly` |
| `OpsPanelFieldLabelWidth` | `float` | private | `const` |
| `IsSandbox` | `bool` | private | `static` |

