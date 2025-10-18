# AutoEngineerControlSetBase Class

**Namespace:** `UI.EngineControls`
**Source:** `AutoEngineerControlSetBase.cs`

## Declaration

```csharp
public abstract class AutoEngineerControlSetBase : EngineControlSetBase
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OrdersHelper` | `AutoEngineerOrdersHelper` | protected | - |

## Methods

### UpdateStatusLabel

```csharp
private void UpdateStatusLabel()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `statusLabel` | `TMP_Text` | private | - |
| `contextualOrdersDropdown` | `DropdownMenu` | private | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_persistence` | `AutoEngineerPersistence` | private | - |

