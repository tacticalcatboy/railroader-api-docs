# RequestSetAccessLevelRuleAttribute Class

**Namespace:** `Game.AccessControl`
**Source:** `RequestSetAccessLevelRuleAttribute.cs`

## Declaration

```csharp
public class RequestSetAccessLevelRuleAttribute : Attribute, IMessageAuthorizationRuleAttribute
```

## Methods

### CheckAuthorization

```csharp
public bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

