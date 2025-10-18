# TestSuite Class

**Namespace:** `Game.Scripting.Testing`
**Source:** `ScriptTestRunner.cs`

## Declaration

```csharp
public class TestSuite
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `SetupClosureName` | `string` | public | - |

## Methods

### GetReport

```csharp
public string GetReport()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Name` | `string` | public | `readonly` |
| `ClosureName` | `string` | public | `readonly` |
| `Suite` | `TestSuite` | public | `readonly` |
| `Status` | `TestStatus` | public | - |
| `FailureMessage` | `string` | public | - |
| `_testPath` | `string` | private | `readonly` |
| `_modulePaths` | `string[]` | private | `readonly` |
| `_hostComponent` | `MonoBehaviour` | private | `readonly` |
| `_testSuites` | `List<TestSuite>` | private | - |
| `TestSuites` | `IReadOnlyList<TestSuite>` | public | - |

