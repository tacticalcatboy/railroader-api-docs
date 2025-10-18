# WeakAction Class

**Namespace:** `GalaSoft.MvvmLight.Helpers`
**Source:** `WeakAction.cs`

## Declaration

```csharp
public class WeakAction : WeakAction, IExecuteWithObject
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Target` | `object` | public | - |

## Methods

### Execute

```csharp
public void Execute(T parameter)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_action` | `Action` | private | `readonly` |
| `_reference` | `WeakReference` | private | - |
| `Action` | `Action` | public | - |
| `_action` | `Action<T>` | private | `readonly` |

