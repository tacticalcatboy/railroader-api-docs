# HostOnlyAuthorizationRuleAttribute Class

**Namespace:** `Game.AccessControl`
**Source:** `HostOnlyAuthorizationRuleAttribute.cs`

## Declaration

```csharp
public class HostOnlyAuthorizationRuleAttribute : Attribute, IMessageAuthorizationRuleAttribute
```

## Methods

### CheckAuthorization

```csharp
public bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

