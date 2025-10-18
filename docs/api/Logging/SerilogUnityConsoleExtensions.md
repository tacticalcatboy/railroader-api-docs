# SerilogUnityConsoleExtensions Class

**Namespace:** `Logging`
**Source:** `SerilogUnityConsoleExtensions.cs`

## Declaration

```csharp
public static class SerilogUnityConsoleExtensions
```

## Methods

### UnityConsole

```csharp
public static LoggerConfiguration UnityConsole(this LoggerSinkConfiguration sinkConfiguration, string outputTemplate = "[{Level:u3}] {Message:lj} {Properties}{NewLine}{Exception}", IFormatProvider formatProvider = null)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `DefaultDebugOutputTemplate` | `string` | private | `const` |

