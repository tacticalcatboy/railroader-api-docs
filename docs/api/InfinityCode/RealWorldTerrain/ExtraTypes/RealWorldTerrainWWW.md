# RealWorldTerrainWWW Class

**Namespace:** `InfinityCode.RealWorldTerrain.ExtraTypes`
**Source:** `RealWorldTerrainWWW.cs`

## Declaration

```csharp
public class RealWorldTerrainWWW
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `helper` | `RealWorldTerrainWWWHelper` | private | - |

## Methods

### LoadImageIntoTexture

```csharp
public void LoadImageIntoTexture(Texture2D tex)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `OnComplete` | `Action<RealWorldTerrainWWW>` | public | - |
| `customData` | `object` | public | - |
| `www` | `UnityWebRequest` | private | - |
| `type` | `RequestType` | private | - |
| `_bytes` | `byte[]` | private | - |
| `_error` | `string` | private | - |
| `_isDone` | `bool` | private | - |
| `_url` | `string` | private | - |
| `responseHeadersString` | `string` | private | - |
| `_id` | `string` | private | - |
| `waitResponse` | `IEnumerator` | private | - |
| `_helper` | `RealWorldTerrainWWWHelper` | private | - |
| `id` | `string` | public | - |
| `isPlaying` | `bool` | private | - |
| `url` | `string` | public | - |

