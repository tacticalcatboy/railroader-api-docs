# MapFeature Class

**Namespace:** `Game.Progression`
**Source:** `MapFeature.cs`

## Declaration

```csharp
public class MapFeature : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Unlocked` | `bool` | public | - |

## Methods

### ToString

```csharp
public override string ToString()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `identifier` | `string` | public | - |
| `displayName` | `string` | public | - |
| `description` | `string` | public | - |
| `defaultEnableInSandbox` | `bool` | public | - |
| `prerequisites` | `MapFeature[]` | public | - |
| `trackGroupsEnableOnUnlock` | `string[]` | public | - |
| `trackGroupsAvailableOnUnlock` | `string[]` | public | - |
| `gameObjectsEnableOnUnlock` | `GameObject[]` | public | - |
| `areasEnableOnUnlock` | `Area[]` | public | - |
| `unlockExcludeIndustries` | `Industry[]` | public | - |
| `unlockIncludeIndustries` | `Industry[]` | public | - |
| `unlockIncludeIndustryComponents` | `IndustryComponent[]` | public | - |

