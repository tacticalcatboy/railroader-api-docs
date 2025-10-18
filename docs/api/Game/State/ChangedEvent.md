# ChangedEvent Struct

**Namespace:** `Game.State`
**Source:** `Ledger.cs`

## Declaration

```csharp
public struct ChangedEvent
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Memo` | `string` | public | - |

## Methods

### PopulateForSave

```csharp
public void PopulateForSave(List<SerializableLedgerEntry> entries)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_entries` | `List<Entry>` | private | `readonly` |
| `_startingBalance` | `int` | private | - |

