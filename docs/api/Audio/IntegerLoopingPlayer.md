# IntegerLoopingPlayer Class

**Namespace:** `Audio`
**Source:** `IntegerLoopingPlayer.cs`

## Declaration

```csharp
public class IntegerLoopingPlayer : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `ConfigureSource` | `Action<IAudioSource>` | public | - |

## Methods

### PrepareSources

```csharp
public void PrepareSources()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `indexedClip` | `IndexedClipDescriptor` | public | - |
| `play` | `bool` | public | - |
| `volume` | `float` | public | - |
| `priority` | `int` | public | - |
| `audioDistance` | `AudioDistance` | public | - |
| `randomize` | `bool` | public | - |
| `averageClipLength` | `float` | public | - |
| `AudioSourceName` | `string` | public | - |
| `_sources` | `List<IAudioSource>` | private | `readonly` |
| `_currentSourceIndex` | `int` | private | - |
| `_nextEndTime` | `double` | private | - |
| `_clips` | `AudioClip[]` | private | - |
| `CrossSamples` | `int` | private | `const` |
| `_innerIndex` | `int` | private | - |
| `_coroutine` | `Coroutine` | private | - |
| `_ownedClips` | `AudioClip[]` | private | - |
| `SourceA` | `IAudioSource` | private | - |
| `SourceB` | `IAudioSource` | private | - |

