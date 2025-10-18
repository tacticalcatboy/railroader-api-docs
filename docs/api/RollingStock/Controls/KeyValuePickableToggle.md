# KeyValuePickableToggle Class

**Namespace:** `RollingStock.Controls`
**Source:** `KeyValuePickableToggle.cs`

## Declaration

```csharp
public class KeyValuePickableToggle : MonoBehaviour, IPickable
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `TooltipText` | `string` | private | - |

## Methods

### Activate

```csharp
public void Activate(PickableActivateEvent evt)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `displayTitle` | `string` | public | - |
| `displayMessageTrue` | `string` | public | - |
| `displayMessageFalse` | `string` | public | - |
| `key` | `string` | public | - |
| `maxPickDistance` | `float` | internal | - |
| `DefaultMaxPickDistance` | `float` | public | `const` |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `MaxPickDistance` | `float` | public | - |
| `Priority` | `int` | public | - |
| `TooltipInfo` | `TooltipInfo` | public | - |
| `ActivationFilter` | `PickableActivationFilter` | public | - |

