# Rule Class

**Namespace:** `InfinityCode.RealWorldTerrain`
**Source:** `RealWorldTerrainVectorTerrainLayerFeature.cs`

## Declaration

```csharp
public class Rule
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `layerNames` | `string[]` | public | `static` |

## Methods

### UpdateHeight

```csharp
public void UpdateHeight()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_layerName` | `string` | private | - |
| `TerrainLayerLineHeight` | `float` | public | `const` |
| `_layerNames` | `string[]` | private | `static` |
| `_landuseNames` | `List<string>` | private | `static` |
| `_landuseOverlayNames` | `List<string>` | private | `static` |
| `_structureNames` | `List<string>` | private | `static` |
| `_waterwayNames` | `List<string>` | private | `static` |
| `terrainLayers` | `List<TerrainLayer>` | public | - |
| `noiseOffset` | `Vector2` | public | - |
| `noiseScale` | `float` | public | - |
| `rules` | `List<Rule>` | public | - |

