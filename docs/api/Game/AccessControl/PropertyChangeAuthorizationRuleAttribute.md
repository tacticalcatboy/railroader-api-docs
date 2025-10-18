# PropertyChangeAuthorizationRuleAttribute Class

**Namespace:** `Game.AccessControl`
**Source:** `PropertyChangeAuthorizationRuleAttribute.cs`

## Declaration

```csharp
public class PropertyChangeAuthorizationRuleAttribute : Attribute, IMessageAuthorizationRuleAttribute
```

## Methods

### CheckAuthorization

```csharp
public bool CheckAuthorization(PlayerId senderPlayerId, AccessLevel senderAccessLevel, IGameMessage message)
```

