# CTCPanelKnob Class

**Namespace:** `Track.Signals`
**Source:** `CTCPanelKnob.cs`

## Declaration

```csharp
public class CTCPanelKnob : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SystemMode` | `SystemMode` | private | `static` |

## Methods

### PlayClick

```csharp
private void PlayClick()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `purpose` | `Purpose` | public | - |
| `knobId` | `string` | public | - |
| `displayNumber` | `string` | public | - |
| `mainLabel` | `TMP_Text` | private | - |
| `leftLabel` | `TMP_Text` | private | - |
| `rightLabel` | `TMP_Text` | private | - |
| `numberLabel` | `TMP_Text` | private | - |
| `audioClips` | `List<AudioClip>` | private | - |
| `_control` | `RadialAnimatedControl` | private | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_isInitial` | `bool` | private | - |
| `Key` | `string` | private | - |
| `CurrentSwitchSetting` | `SwitchSetting` | public | - |
| `CurrentDirection` | `SignalDirection` | public | - |

