# AutoEngineerWaypointOverlayController Class

**Namespace:** `UI.EngineControls`
**Source:** `AutoEngineerWaypointOverlayController.cs`

## Declaration

```csharp
public class AutoEngineerWaypointOverlayController : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `AutoEngineerWaypointOverlayController` | public | `static` |

## Methods

### WaypointDidChange

```csharp
public void WaypointDidChange(OrderWaypoint? ordersWaypoint)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_shared` | `AutoEngineerWaypointOverlayController` | private | `static` |
| `_locations` | `List<Location>` | private | - |
| `_hasMoreLocations` | `bool` | private | - |
| `_currentArrowKeys` | `List<int>` | private | - |
| `TagsVisible` | `bool` | private | - |
| `Locomotive` | `BaseLocomotive` | private | - |
| `ArrowOverlayController` | `ArrowOverlayController` | private | `static` |

