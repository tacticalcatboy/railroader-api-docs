# MapFeatureManager Class

**Namespace:** `Game.Progression`
**Source:** `MapFeatureManager.cs`

## Declaration

```csharp
public class MapFeatureManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `MapFeatureManager` | public | `static` |

## Methods

### SetFeatureEnabled

```csharp
public void SetFeatureEnabled(MapFeature feature, bool unlocked)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_features` | `MapFeature[]` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_keyChangeObserver` | `IDisposable` | private | - |
| `_progressionDisablabledSet` | `HashSet<IProgressionDisablable>` | private | `readonly` |
| `_scheduledRebuildCollectionsIndustryDidChange` | `Coroutine` | private | - |
| `_scheduledRebuildTrack` | `Coroutine` | private | - |
| `ObjectId` | `string` | internal | `const` |
| `FeaturesKey` | `string` | private | `const` |
| `_instance` | `MapFeatureManager` | private | `static` |
| `AvailableFeatures` | `IEnumerable<MapFeature>` | public | - |

