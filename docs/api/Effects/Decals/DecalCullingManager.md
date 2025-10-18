# DecalCullingManager Class

**Namespace:** `Effects.Decals`
**Source:** `DecalCullingManager.cs`

## Declaration

```csharp
public class DecalCullingManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Shared` | `DecalCullingManager` | public | `static` |

## Methods

### CalculateNativeFrustumPlanes

```csharp
private static void CalculateNativeFrustumPlanes(Vector3 cameraForward, Plane[] frustumPlanes, Vector3 cameraPosition, NativeArray<float4> nativePlanes, float scale)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DecalProjector` | `DecalProjector` | public | - |
| `VisibleDidChange` | `Action<bool>` | public | - |
| `DecalPositions` | `NativeArray<float3>` | public | - |
| `DecalForwards` | `NativeArray<float3>` | public | - |
| `DecalSizes` | `NativeArray<float3>` | public | - |
| `CameraPosition` | `float3` | public | - |
| `CullDistance` | `float` | public | - |
| `FrustumPlanes` | `NativeArray<float4>` | public | - |
| `ProjectionMatrix` | `float4x4` | public | - |
| `WorldToViewMatrix` | `float4x4` | public | - |
| `MinScreenSize` | `float` | public | - |
| `ScreenHeight` | `float` | public | - |
| `DecalVisibility` | `NativeArray<bool>` | public | - |
| `min` | `float3` | public | - |
| `max` | `float3` | public | - |
| `Center` | `float3` | public | - |
| `Size` | `float3` | public | - |
| `cullDistance` | `float` | private | - |
| `updateInterval` | `float` | private | - |
| `screenSizeThresholdHighQuality` | `float` | private | - |
| `screenSizeThresholdLowQuality` | `float` | private | - |
| `frustumScale` | `float` | private | - |
| `decalBudget` | `int` | private | - |
| `cameraVelocityThreshold` | `float` | private | - |
| `cameraAngularVelocityThreshold` | `float` | private | - |
| `_mainCamera` | `Camera` | private | - |
| `_decalProjectors` | `List<Entry>` | private | `readonly` |
| `_timeSinceLastUpdate` | `float` | private | - |
| `_updateFast` | `bool` | private | - |
| `_visibleCount` | `int` | private | - |
| `_screenSizeThreshold` | `float` | private | - |
| `_frustumPlanes` | `Plane[]` | private | - |
| `_lastCameraPosition` | `Vector3` | private | - |
| `_lastCameraEulerAngles` | `Vector3` | private | - |
| `_shared` | `DecalCullingManager` | private | `static` |

