# SwitchListPanel Class

**Namespace:** `UI.SwitchList`
**Source:** `SwitchListPanel.cs`

## Declaration

```csharp
public class SwitchListPanel : MonoBehaviour
```

## Methods

### PeriodicRefresh

```csharp
private IEnumerator PeriodicRefresh()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `emptyStateLabel` | `TMP_Text` | private | - |
| `toolsMenu` | `DropdownMenu` | private | - |
| `_refreshCoroutine` | `Coroutine` | private | - |
| `_switchList` | `OpsCarList` | private | `readonly` |
| `trainController` | `TrainController` | private | - |
| `TrainCrew` | `TrainCrew` | private | `static` |
| `Shared` | `SwitchListPanel` | public | `static` |

