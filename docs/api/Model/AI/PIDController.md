# PIDController Class

**Namespace:** `Model.AI`
**Source:** `PIDController.cs`

## Declaration

```csharp
public class PIDController
```

## Methods

### CopyTo

```csharp
public void CopyTo(PIDController other)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `proportionalGain` | `float` | private | - |
| `integralGain` | `float` | public | - |
| `derivativeGain` | `float` | public | - |
| `integralGrowth` | `float` | public | - |
| `integralDecay` | `float` | private | - |
| `_previousError` | `float` | private | - |
| `_integrator` | `float` | private | - |
| `_previousControl` | `float` | private | - |
| `_previousDerivative` | `float` | private | - |
| `_previousIntegrator` | `float` | private | - |
| `errorRange` | `FloatRange` | public | - |
| `integratorRange` | `FloatRange` | public | - |
| `outputRange` | `FloatRange` | public | - |
| `maximumStep` | `float` | private | - |
| `PreviousError` | `float` | public | - |
| `Integrator` | `float` | public | - |
| `DebugIntegrator` | `float` | public | - |
| `DebugDerivative` | `float` | public | - |

