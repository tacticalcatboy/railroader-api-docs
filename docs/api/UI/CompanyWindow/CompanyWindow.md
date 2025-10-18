# CompanyWindow Class

**Namespace:** `UI.CompanyWindow`
**Source:** `CompanyWindow.cs`

## Declaration

```csharp
public class CompanyWindow : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ShownPath` | `string` | public | - |

## Methods

### WindowShownDidChange

```csharp
private void WindowShownDidChange(bool shown)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TabIdRailroad` | `string` | private | `const` |
| `TabIdMilestones` | `string` | private | `const` |
| `TabIdFinance` | `string` | private | `const` |
| `TabIdLocations` | `string` | private | `const` |
| `TabIdEquipment` | `string` | private | `const` |
| `TabIdEmployees` | `string` | private | `const` |
| `TabIdCrews` | `string` | private | `const` |
| `TabIdSettings` | `string` | private | `const` |
| `_window` | `Window` | private | - |
| `_instance` | `CompanyWindow` | private | `static` |
| `_selectedTabState` | `UIState<string>` | private | `readonly` |
| `_selectedGoalsItem` | `UIState<string>` | private | `readonly` |
| `_selectedLocationsItem` | `UIState<string>` | private | `readonly` |
| `_selectedSettingsItem` | `UIState<string>` | private | `readonly` |
| `_selectedCarItem` | `UIState<string>` | private | `readonly` |
| `_selectedTrainCrewId` | `UIState<string>` | private | `readonly` |
| `_selectedPlayerId` | `UIState<string>` | private | `readonly` |
| `_panel` | `UIPanel` | private | - |
| `Shared` | `CompanyWindow` | public | `static` |

