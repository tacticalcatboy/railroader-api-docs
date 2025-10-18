# Descriptor Struct

**Namespace:** `UI`
**Source:** `LocationIndicatorController.cs`

## Declaration

```csharp
public struct Descriptor
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Compass` | `CompassHUD` | private | - |

## Methods

### Awake

```csharp
private void Awake()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Title` | `string` | public | `readonly` |
| `Subtitle` | `string` | public | - |
| `_targetCarId` | `string` | private | - |
| `_targetGamePosition` | `Vector3` | private | - |
| `_instance` | `LocationIndicatorController` | private | `static` |
| `indicatorPrefab` | `BillboardLocationIndicator` | public | - |
| `calloutPrefab` | `Callout` | public | - |
| `canvas` | `Canvas` | public | - |
| `_compass` | `CompassHUD` | private | - |
| `_camera` | `Camera` | private | - |
| `_contentUpdateCoroutine` | `Coroutine` | private | - |
| `Shared` | `LocationIndicatorController` | public | `static` |

