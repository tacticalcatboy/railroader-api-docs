# Progression Class

**Namespace:** `Game.Progression`
**Source:** `Progression.cs`

## Declaration

```csharp
public class Progression : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `UnlockedSectionIds` | `IEnumerable<string>` | private | - |

## Methods

### PrerequisitesMet

```csharp
private bool PrerequisitesMet(Section section)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `identifier` | `string` | public | - |
| `mapFeatureManager` | `MapFeatureManager` | public | - |
| `enableFeaturesAtStart` | `MapFeature[]` | private | - |
| `_keyValueObject` | `KeyValueObject` | private | - |
| `_keyChangeObserver` | `IDisposable` | private | - |
| `_instance` | `Progression` | private | `static` |
| `KeyUnlocked` | `string` | private | `const` |
| `Shared` | `Progression` | public | `static` |

