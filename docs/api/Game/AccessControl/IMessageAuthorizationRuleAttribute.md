# IMessageAuthorizationRuleAttribute Interface

**Namespace:** `Game.AccessControl`
**Source:** `IMessageAuthorizationRuleAttribute.cs`

## Declaration

```csharp
public interface IMessageAuthorizationRuleAttribute
```

## Methods

### CheckAuthorization

```csharp
bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

