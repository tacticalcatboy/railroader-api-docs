# CharacterController Class

**Namespace:** `Character`
**Source:** `CharacterController.cs`

## Declaration

```csharp
public class CharacterController : MonoBehaviour, ICharacterController
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `IsInAir` | `bool` | public | - |

## Methods

### OnMovementHit

```csharp
public void OnMovementHit(Collider hitCollider, Vector3 hitNormal, Vector3 hitPoint, ref HitStabilityReport hitStabilityReport)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `motor` | `KinematicCharacterMotor` | public | - |
| `maxStableMoveSpeed` | `float` | public | - |
| `stableMovementAccelSharpness` | `float` | public | - |
| `stableMovementDecelSharpness` | `float` | public | - |
| `orientationSharpness` | `float` | public | - |
| `runMoveSpeed` | `float` | public | - |
| `maxAirMoveSpeed` | `float` | public | - |
| `airAccelerationSpeed` | `float` | public | - |
| `drag` | `float` | public | - |
| `allowJumpingWhenSliding` | `bool` | public | - |
| `jumpUpSpeed` | `float` | public | - |
| `jumpScalableForwardSpeed` | `float` | public | - |
| `jumpPreGroundingGraceTime` | `float` | public | - |
| `jumpPostGroundingGraceTime` | `float` | public | - |
| `ladderSpeedNormal` | `float` | public | - |
| `ladderSpeedFast` | `float` | public | - |
| `ignoredColliders` | `List<Collider>` | public | - |
| `gravity` | `Vector3` | public | - |
| `cameraContainer` | `Transform` | public | - |
| `crouchedCapsuleHeight` | `float` | public | - |
| `maintainUpDegreesPerSecond` | `float` | public | - |
| `_probedColliders` | `Collider[]` | private | - |
| `_probedHits` | `RaycastHit[]` | private | - |
| `_moveInputVector` | `Vector3` | private | - |
| `_lookInputRotation` | `Quaternion` | private | - |
| `_jumpRequested` | `bool` | private | - |
| `_jumpConsumed` | `bool` | private | - |
| `_jumpedThisFrame` | `bool` | private | - |
| `_jumpedFromLadder` | `bool` | private | - |
| `_timeSinceJumpRequested` | `float` | private | - |
| `_timeSinceLastAbleToJump` | `float` | private | - |
| `_internalVelocityAdd` | `Vector3` | private | - |
| `_shouldBeCrouching` | `bool` | private | - |
| `_isCrouching` | `bool` | private | - |
| `_inputRun` | `bool` | private | - |
| `lastInnerNormal` | `Vector3` | private | - |
| `lastOuterNormal` | `Vector3` | private | - |
| `_initialCapsuleRadius` | `float` | private | - |
| `_initialCapsuleHeight` | `float` | private | - |
| `_tmpTransientRot` | `Quaternion` | private | - |
| `_attachState` | `AttachState` | private | - |
| `_anchoringTimer` | `float` | private | - |
| `AnchoringDuration` | `float` | private | `const` |
| `eyeHeightStanding` | `float` | public | - |
| `eyeHeightSeated` | `float` | public | - |
| `_seat` | `Seat` | private | - |
| `_seatStickyRemaining` | `float` | private | - |
| `_ladder` | `Ladder` | private | - |
| `_ladderLocalPosition` | `Vector3` | private | - |
| `_ladderDuration` | `float` | private | - |
| `leanDistance` | `float` | public | - |
| `_cameraSeated` | `bool` | private | - |
| `_cameraContainerMoveId` | `int` | private | - |
| `OnSeatDidChange` | `Action` | public | - |
| `OnLadderDidChange` | `Action` | public | - |
| `_hasAttachedRigidbody` | `bool` | private | - |
| `AnchoringParameter` | `float` | private | - |
| `Seat` | `Seat` | public | - |
| `IsSeated` | `bool` | public | - |
| `IsOnLadder` | `bool` | public | - |
| `LadderStickyRemaining` | `float` | private | - |

