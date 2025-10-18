# GameInput Class

**Namespace:** `UI`
**Source:** `GameInput.cs`

## Declaration

```csharp
public class GameInput : MonoBehaviour
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsShiftDown` | `bool` | public | `static` |

## Methods

### UnregisterEscapeHandler

```csharp
public static void UnregisterEscapeHandler(EscapeHandler handler)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_inputMode` | `InputMode` | private | `static` |
| `pressInput` | `PressInput` | private | - |
| `inputActions` | `InputActionAsset` | public | - |
| `_gameActionMap` | `InputActionMap` | private | - |
| `_focusPause` | `bool` | private | - |
| `_help` | `InputAction` | private | - |
| `_cameraJumpToSeat` | `InputAction` | private | - |
| `_cameraJumpToHead` | `InputAction` | private | - |
| `_cameraJumpToTail` | `InputAction` | private | - |
| `_cameraFollowHead` | `InputAction` | private | - |
| `_cameraFollowTail` | `InputAction` | private | - |
| `_cameraSelectFirstPerson` | `InputAction` | private | - |
| `_cameraSelectStrategy` | `InputAction` | private | - |
| `_cameraSelectDispatcher` | `InputAction` | private | - |
| `_cameraJumpStrategyToAvatar` | `InputAction` | private | - |
| `_crouchAction` | `InputAction` | private | - |
| `_jumpAction` | `InputAction` | private | - |
| `_leanLeftAction` | `InputAction` | private | - |
| `_leanRightAction` | `InputAction` | private | - |
| `_moveAction` | `InputAction` | internal | - |
| `_runAction` | `InputAction` | internal | - |
| `_veryFastAction` | `InputAction` | private | - |
| `_teleportAction` | `InputAction` | internal | - |
| `_placeFlareAction` | `InputAction` | private | - |
| `_hornAction` | `InputAction` | private | - |
| `_hornExpressionEnableAction` | `InputAction` | private | - |
| `_hornExpressionValueAction` | `InputAction` | private | - |
| `_autoEngineerWaypointSelect` | `InputAction` | private | - |
| `_headlightForwardAction` | `InputAction` | private | - |
| `_headlightBackAction` | `InputAction` | private | - |
| `_reverserForward` | `InputAction` | private | - |
| `_reverserBack` | `InputAction` | private | - |
| `_throttleUp` | `InputAction` | private | - |
| `_throttleDown` | `InputAction` | private | - |
| `_trainBrakeApply` | `InputAction` | private | - |
| `_trainBrakeRelease` | `InputAction` | private | - |
| `_locomotiveBrakeApply` | `InputAction` | private | - |
| `_locomotiveBrakeRelease` | `InputAction` | private | - |
| `_bell` | `InputAction` | private | - |
| `_cylinderCock` | `InputAction` | private | - |
| `_resetFOVAction` | `InputAction` | private | - |
| `_showPlacerAction` | `InputAction` | private | - |
| `_toggleMapAction` | `InputAction` | private | - |
| `_toggleTagsAction` | `InputAction` | private | - |
| `_toggleSwitchListAction` | `InputAction` | private | - |
| `_toggleTimetableAction` | `InputAction` | private | - |
| `_toggleTimeWindowAction` | `InputAction` | private | - |
| `_toggleCompanyWindowAction` | `InputAction` | private | - |
| `_togglePreferencesWindowAction` | `InputAction` | private | - |
| `_toggleLanternAction` | `InputAction` | private | - |
| `_pushCarAction` | `InputAction` | private | - |
| `_togglePhotoModeAction` | `InputAction` | private | - |
| `_toggleConsoleAction` | `InputAction` | private | - |
| `_toggleEngineRosterAction` | `InputAction` | private | - |
| `_queryAction` | `InputAction` | private | - |
| `_copyLocationAction` | `InputAction` | private | - |
| `_toggleContextMenuAction` | `InputAction` | private | - |
| `_moveTrainAction` | `InputAction` | private | - |
| `_recallSelectionAction` | `InputAction` | private | - |
| `_cycleSelectionAction` | `InputAction` | private | - |
| `_quickSearchAction` | `InputAction` | private | - |
| `_closeWindowAction` | `InputAction` | private | - |
| `_showPauseMenuAction` | `InputAction` | private | - |
| `_ffwdUpAction` | `InputAction` | private | - |
| `_ffwdDownAction` | `InputAction` | private | - |
| `MovementCounter` | `Vector4` | public | - |
| `MovementJumped` | `bool` | public | - |
| `EnableMovementCounters` | `bool` | public | - |
| `KeyRebinds` | `string` | private | `const` |
| `_reverserForwardSlowRepeating` | `VirtualRepeatingInput` | private | - |
| `_reverserBackSlowRepeating` | `VirtualRepeatingInput` | private | - |
| `_throttleUpSlowRepeating` | `VirtualRepeatingInput` | private | - |
| `_throttleDownSlowRepeating` | `VirtualRepeatingInput` | private | - |
| `_reverserForwardRepeating` | `VirtualRepeatingInput` | private | - |
| `_reverserBackRepeating` | `VirtualRepeatingInput` | private | - |
| `_throttleUpRepeating` | `VirtualRepeatingInput` | private | - |
| `_throttleDownRepeating` | `VirtualRepeatingInput` | private | - |
| `_trainBrakeApplyRepeating` | `VirtualRepeatingInput` | private | - |
| `_trainBrakeReleaseRepeating` | `VirtualRepeatingInput` | private | - |
| `_locomotiveBrakeApplyRepeating` | `VirtualRepeatingInput` | private | - |
| `_locomotiveBrakeReleaseRepeating` | `VirtualRepeatingInput` | private | - |
| `MovementInputEnabled` | `bool` | public | `static` |
| `MoveVector` | `Vector2` | public | - |
| `ModifierRun` | `bool` | public | - |
| `ModifierVeryFast` | `bool` | public | - |
| `Teleport` | `bool` | public | - |
| `PlaceFlare` | `bool` | public | - |
| `HornExpressionEnabledThisFrame` | `bool` | public | - |
| `HornExpressionEnabled` | `bool` | public | - |
| `HornExpressionValue` | `float` | public | - |
| `ShowHelp` | `bool` | public | - |
| `CameraJumpToSeat` | `bool` | public | - |
| `CameraJumpToHead` | `bool` | public | - |
| `CameraJumpToTail` | `bool` | public | - |
| `CameraFollowHead` | `bool` | public | - |
| `CameraFollowTail` | `bool` | public | - |
| `CameraSelectFirstPerson` | `bool` | public | - |
| `CameraSelectStrategy` | `bool` | public | - |
| `CameraSelectDispatcher` | `bool` | public | - |
| `CameraJumpStrategyToAvatar` | `bool` | public | - |
| `CrouchDown` | `bool` | public | - |
| `CrouchUp` | `bool` | public | - |
| `JumpDown` | `bool` | public | - |
| `PrimaryPressStartedThisFrame` | `bool` | public | - |
| `PrimaryPressEndedThisFrame` | `bool` | public | - |
| `SecondaryLongPressBeganThisFrame` | `bool` | public | - |
| `SecondaryLongPressEndedThisFrame` | `bool` | public | - |
| `LookDelta` | `Vector2` | public | - |
| `LeanLeft` | `bool` | public | - |
| `LeanRight` | `bool` | public | - |
| `InputResetFOV` | `bool` | public | - |
| `InputShowPlacer` | `bool` | private | - |
| `InputToggleMap` | `bool` | private | - |
| `InputToggleTags` | `bool` | public | - |
| `InputToggleSwitchList` | `bool` | private | - |
| `InputToggleTimetable` | `bool` | private | - |
| `InputToggleTimeWindow` | `bool` | private | - |
| `InputToggleCompanyWindow` | `bool` | private | - |
| `InputTogglePreferencesWindow` | `bool` | private | - |
| `InputToggleLantern` | `bool` | private | - |
| `InputPushCar` | `bool` | private | - |
| `InputTogglePhotoMode` | `bool` | public | - |
| `InputToggleConsole` | `bool` | public | - |
| `Query` | `bool` | public | - |
| `CopyLocation` | `bool` | public | - |
| `InputFfwdUp` | `bool` | public | - |
| `InputFfwdDown` | `bool` | public | - |
| `ReverserForwardRepeating` | `bool` | public | - |
| `ReverserBackRepeating` | `bool` | public | - |
| `ThrottleUpRepeating` | `bool` | public | - |
| `ThrottleDownRepeating` | `bool` | public | - |
| `ReverserForward` | `bool` | public | - |
| `ReverserBack` | `bool` | public | - |
| `ThrottleUp` | `bool` | public | - |
| `ThrottleDown` | `bool` | public | - |
| `TrainBrakeApply` | `bool` | public | - |
| `TrainBrakeRelease` | `bool` | public | - |
| `LocomotiveBrakeApply` | `bool` | public | - |
| `LocomotiveBrakeRelease` | `bool` | public | - |
| `Bell` | `bool` | public | - |
| `CylinderCock` | `bool` | public | - |

