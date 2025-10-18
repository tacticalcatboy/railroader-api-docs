# StateManager Class

**Namespace:** `Game.State`
**Source:** `StateManager.cs`

## Declaration

```csharp
public class StateManager : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `HasTutorial` | `bool` | public | - |

## Methods

### GetBalance

```csharp
public int GetBalance()
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `gameManager` | `GlobalGameManager` | private | - |
| `audioLibrary` | `AudioLibrary` | private | - |
| `_propertyObjectManager` | `PropertyObjectManager` | private | - |
| `_storage` | `GameStorage` | private | - |
| `_observers` | `HashSet<IDisposable>` | private | `readonly` |
| `_playersManager` | `PlayersManager` | private | - |
| `_playerPropertiesManager` | `PlayerPropertiesManager` | private | - |
| `_audioPlayer` | `ScheduledAudioPlayer` | private | - |
| `Ledger` | `Ledger` | public | `readonly` |
| `_loanManager` | `LoanManager` | private | - |
| `_saveManager` | `SaveManager` | private | - |
| `_timeObserver` | `TimeObserver` | private | - |
| `_setupDescriptor` | `SetupDescriptor` | private | - |
| `IsHost` | `bool` | public | `static` |
| `HasTrainmasterAccess` | `bool` | public | `static` |
| `IsSandbox` | `bool` | public | `static` |
| `_trainController` | `TrainController` | private | - |
| `opsController` | `OpsController` | private | - |
| `Storage` | `GameStorage` | public | - |
| `PlayersManager` | `PlayersManager` | public | - |
| `AudioPlayer` | `ScheduledAudioPlayer` | public | - |
| `LoanManager` | `LoanManager` | public | - |
| `SaveManager` | `SaveManager` | public | - |
| `HasRestoredProperties` | `bool` | public | - |

