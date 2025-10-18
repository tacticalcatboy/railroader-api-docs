# ControlExtensions Class

**Namespace:** `RollingStock.ContinuousControls`
**Source:** `ControlExtensions.cs`

## Declaration

```csharp
public static class ControlExtensions
```

## Methods

### ConfigurePropertyChange

```csharp
public static void ConfigurePropertyChange(this ContinuousControl control, Func<float, PropertyChange> propertyChangeFunc, Func<string> tooltipText = null)
```

