# TrainControllerExtensions Class

**Namespace:** `Track`
**Source:** `TrainControllerExtensions.cs`

## Declaration

```csharp
public static class TrainControllerExtensions
```

## Methods

### FindOpenSpaceFromLower

```csharp
public static bool FindOpenSpaceFromLower(this TrainController trainController, TrackSpan span, float lengthInMeters, Func<Car, bool> canCoupleToCar, out Location location, out Car car)
```

