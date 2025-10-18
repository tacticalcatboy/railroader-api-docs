# World Struct

**Namespace:** `Game.Persistence`
**Source:** `WorldStore.cs`

## Declaration

```csharp
public struct World
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `LedgerEntries` | `List<SerializableLedgerEntry>` | public | - |

## Methods

### FindSaveInfos

```csharp
public static List<SaveInfo> FindSaveInfos()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Name` | `string` | public | - |
| `Date` | `DateTime` | public | - |
| `Version` | `int` | public | - |
| `Snapshot` | `Snapshot` | public | - |
| `Extension` | `string` | private | `const` |
| `SavePath` | `string` | private | `static` |

