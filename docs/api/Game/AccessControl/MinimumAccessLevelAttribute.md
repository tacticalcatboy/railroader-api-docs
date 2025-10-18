# MinimumAccessLevelAttribute Class

**Namespace:** `Game.AccessControl`
**Source:** `MinimumAccessLevelAttribute.cs`

## Declaration

```csharp
public class MinimumAccessLevelAttribute : Attribute, IMessageAuthorizationRuleAttribute
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `MinimumLevel` | `AccessLevel` | public | - |

## Methods

### CheckAuthorization

```csharp
public bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

