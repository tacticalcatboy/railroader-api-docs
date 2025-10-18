# TrainBrakeDisplay Class

**Namespace:** `UI`
**Source:** `TrainBrakeDisplay.cs`

## Declaration

```csharp
public class TrainBrakeDisplay : MonoBehaviour
```

## Methods

### ColorForPsi

```csharp
private Color ColorForPsi(float psi)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `brakeCylinderGradient` | `Gradient` | private | - |
| `handbrakeAppliedColor` | `Color` | private | - |
| `derailedColor` | `Color` | private | - |
| `airIssueColor` | `Color` | private | - |
| `carTile` | `Sprite` | private | - |
| `locomotiveTile` | `Sprite` | private | - |
| `airIssueTile` | `Sprite` | private | - |
| `_rectTransform` | `RectTransform` | private | - |
| `_carImages` | `List<Image>` | private | `readonly` |
| `_airImages` | `List<Image>` | private | `readonly` |
| `_lastNumCars` | `int` | private | - |
| `_spacing` | `float` | private | - |
| `_imageWidth` | `float` | private | - |
| `MaxSpacing` | `float` | private | `const` |
| `MaxImageWidth` | `float` | private | `const` |
| `ImageHeight` | `float` | private | `const` |
| `_trainController` | `TrainController` | private | - |

