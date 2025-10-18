# ActivateState Class

**Namespace:** `UI`
**Source:** `PressInput.cs`

## Declaration

```csharp
private class ActivateState
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `PrimaryPressStartedThisFrame` | `bool` | public | - |

## Methods

### Update

```csharp
private void Update()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `gameInput` | `GameInput` | private | - |
| `MovedThreshold` | `float` | private | `const` |
| `_primaryState` | `ActivateState` | private | - |
| `_secondaryState` | `ActivateState` | private | - |
| `PrimaryPressEndedThisFrame` | `bool` | public | - |
| `SecondaryPressedThisFrame` | `bool` | public | - |
| `SecondaryLongPressBeganThisFrame` | `bool` | public | - |
| `SecondaryLongPressEndedThisFrame` | `bool` | public | - |

