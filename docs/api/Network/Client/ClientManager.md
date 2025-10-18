# ClientManager Class

**Namespace:** `Network.Client`
**Source:** `ClientManager.cs`

## Declaration

```csharp
public class ClientManager : MonoBehaviour, IClientDelegate
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsClientStatusActive` | `bool` | public | - |

## Methods

### ClientDidReceiveTimeSync

```csharp
public void ClientDidReceiveTimeSync(TimeSync timeSync)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_client` | `ClientManager` | private | `readonly` |
| `_client` | `GameClient` | private | - |
| `_becameActiveCompletionSource` | `TaskCompletionSource<bool>` | private | - |
| `_timeSynchronizer` | `TimeSynchronizer` | private | - |
| `_password` | `string` | private | - |
| `_inTransaction` | `int` | private | - |
| `_transactionMessages` | `List<IGameMessage>` | private | `readonly` |

