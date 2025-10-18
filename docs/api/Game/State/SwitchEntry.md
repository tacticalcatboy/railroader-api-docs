# SwitchEntry Struct

**Namespace:** `Game.State`
**Source:** `AuditManager.cs`

## Declaration

```csharp
private struct SwitchEntry
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `AuditManager` | public | `static` |

## Methods

### TryGetSwitchText

```csharp
public bool TryGetSwitchText(string nodeId, out string report)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Timestamp` | `int` | public | `readonly` |
| `Action` | `string` | public | `readonly` |
| `Requester` | `string` | public | `readonly` |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `KeyValueIdentifier` | `string` | private | `const` |

