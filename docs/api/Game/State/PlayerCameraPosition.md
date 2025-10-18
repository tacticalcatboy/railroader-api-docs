# PlayerCameraPosition Struct

**Namespace:** `Game.State`
**Source:** `PlayersManager.cs`

## Declaration

```csharp
private struct PlayerCameraPosition
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `AllPlayers` | `IEnumerable<IPlayer>` | public | - |

## Methods

### HandleRequestCreateTrainCrew

```csharp
public void HandleRequestCreateTrainCrew(IPlayer sender, Snapshot.TrainCrew trainCrew)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Position` | `Vector3` | public | `readonly` |
| `Time` | `float` | public | `readonly` |
| `_orderedTrainCrews` | `List<TrainCrew>` | private | - |
| `_localPlayer` | `LocalPlayer` | private | `readonly` |
| `_hasNotifiedOfPlayers` | `bool` | private | - |
| `RemotePlayers` | `IEnumerable<RemotePlayer>` | public | - |
| `TrainCrews` | `IReadOnlyList<TrainCrew>` | public | - |
| `LocalPlayer` | `LocalPlayer` | public | - |
| `MyTrainCrew` | `TrainCrew` | public | - |

