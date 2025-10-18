# EngineRosterRow Class

**Namespace:** `UI.EngineRoster`
**Source:** `EngineRosterRow.cs`

## Declaration

```csharp
public class EngineRosterRow : MonoBehaviour, ILazyScrollListCell
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ListIndex` | `int` | public | - |

## Methods

### ActionInspect

```csharp
public void ActionInspect()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `rectTransform` | `RectTransform` | private | - |
| `nameLabel` | `TMP_Text` | private | - |
| `infoLabel` | `TMP_Text` | private | - |
| `crewLabel` | `TMP_Text` | private | - |
| `favoriteToggle` | `Toggle` | private | - |
| `selectedToggle` | `Toggle` | private | - |
| `nameTooltip` | `UITooltipProvider` | private | - |
| `crewTooltip` | `UITooltipProvider` | private | - |
| `infoTooltip` | `UITooltipProvider` | private | - |
| `_engine` | `BaseLocomotive` | private | - |
| `_parent` | `EngineRosterPanel` | private | - |
| `_persistence` | `AutoEngineerPersistence` | private | - |
| `_crewComponents` | `List<string>` | private | `readonly` |
| `RectTransform` | `RectTransform` | public | - |

