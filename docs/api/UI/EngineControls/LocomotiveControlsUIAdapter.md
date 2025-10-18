# LocomotiveControlsUIAdapter Class

**Namespace:** `UI.EngineControls`
**Source:** `LocomotiveControlsUIAdapter.cs`

## Declaration

```csharp
public class LocomotiveControlsUIAdapter : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SimplifiedControls` | `bool` | private | - |

## Methods

### DidClickFollow

```csharp
public void DidClickFollow()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `nameLabel` | `TMP_Text` | private | - |
| `infoALabel` | `TMP_Text` | private | - |
| `infoBLabel` | `TMP_Text` | private | - |
| `speedLabel` | `TMP_Text` | private | - |
| `modeDropdown` | `TMP_Dropdown` | private | - |
| `optionsDropdown` | `DropdownMenu` | private | - |
| `controls` | `RectTransform` | private | - |
| `manualControls` | `EngineControlSetBase` | private | - |
| `simplifiedControls` | `EngineControlSetBase` | private | - |
| `aiRoadControls` | `EngineControlSetBase` | private | - |
| `aiYardControls` | `EngineControlSetBase` | private | - |
| `aiWaypointControls` | `EngineControlSetBase` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_speedometerCoroutine` | `Coroutine` | private | - |
| `_controlSets` | `List<EngineControlSetBase>` | private | - |
| `_persistence` | `AutoEngineerPersistence` | private | - |
| `_ordersObserver` | `IDisposable` | private | - |
| `Locomotive` | `BaseLocomotive` | private | `static` |

