# DefinitionChecker Class

**Namespace:** `Model.Database`
**Source:** `DefinitionChecker.cs`

## Declaration

```csharp
internal class DefinitionChecker
```

## Methods

### Warning

```csharp
private void Warning(string message)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_warnings` | `List<string>` | private | `readonly` |
| `_errors` | `List<string>` | private | `readonly` |
| `_objectIdentifier` | `string` | private | `readonly` |
| `_packIdentifier` | `string` | private | `readonly` |
| `_store` | `AssetPackRuntimeStore` | private | `readonly` |
| `Warnings` | `IReadOnlyCollection<string>` | public | - |
| `Errors` | `IReadOnlyCollection<string>` | public | - |

