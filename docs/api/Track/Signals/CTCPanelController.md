# CTCPanelController Class

**Namespace:** `Track.Signals`
**Source:** `CTCPanelController.cs`

## Declaration

```csharp
public class CTCPanelController : GameBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `CTCPanelController` | public | `static` |

## Methods

### CacheBlocksIfNeeded

```csharp
private void CacheBlocksIfNeeded()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ModeKey` | `string` | public | `const` |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_resetButtonIds` | `HashSet<string>` | private | `readonly` |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_storage` | `SignalStorage` | private | - |
| `ctcGameObject` | `GameObject` | private | - |
| `codeButtonAudioClips` | `List<AudioClip>` | private | - |
| `relayPlayer` | `IntegerLoopingPlayer` | private | - |
| `_interlockingOccupancyObservers` | `HashSet<IDisposable>` | private | `readonly` |
| `_panelButtons` | `CTCPanelButton[]` | private | - |
| `_panelGroups` | `CTCPanelGroup[]` | private | - |
| `SystemMode` | `SystemMode` | public | - |

