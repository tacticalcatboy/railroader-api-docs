# RequestSetTrainCrewMembershipRuleAttribute Class

**Namespace:** `Game.AccessControl`
**Source:** `RequestSetTrainCrewMembershipRuleAttribute.cs`

## Declaration

```csharp
public class RequestSetTrainCrewMembershipRuleAttribute : Attribute, IMessageAuthorizationRuleAttribute
```

## Methods

### CheckAuthorization

```csharp
public bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

