# CarCustomizeWindow Class

**Namespace:** `UI.CarCustomizeWindow`
**Source:** `CarCustomizeWindow.cs`

## Declaration

```csharp
public class CarCustomizeWindow : MonoBehaviour, IBuilderWindow
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CanChangeReportingMark` | `bool` | private | - |

## Methods

### BuildLetteringTabDecal

```csharp
private void BuildLetteringTabDecal(UIPanelBuilder builder, List<DecalComponent> decalComponents)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_window` | `Window` | private | - |
| `_panel` | `UIPanel` | private | - |
| `_selectedTabState` | `UIState<int>` | private | `readonly` |
| `_car` | `Car` | private | - |
| `LetteringBasicKey` | `string` | public | `const` |
| `Instance` | `CarCustomizeWindow` | private | `static` |
| `IsSandbox` | `bool` | private | `static` |
| `CanRenumber` | `bool` | private | - |

