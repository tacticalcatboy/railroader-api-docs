# Car Class

**Namespace:** `Model`
**Source:** `Car.cs`

## Declaration

```csharp
public class Car : MonoBehaviour, IDefinitionReferenceResolver, IPropertyAccessControlDelegate
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CurrentTrackCurvature` | `float` | public | - |

## Methods

### UpdateBrakeApplied

```csharp
protected virtual void UpdateBrakeApplied(bool brakeApplied)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `Coupler` | `Coupler` | public | - |
| `CutLever` | `CutLever` | public | - |
| `IsCoupled` | `bool` | public | - |
| `IsAirConnected` | `bool` | public | - |
| `AnglecockSetting` | `float` | public | - |
| `AirPressure` | `float` | public | - |
| `NeedsConnectionUpdate` | `bool` | public | - |
| `_other` | `EndGear` | private | - |
| `_isPopulated` | `bool` | private | - |
| `IsAnglecockOpen` | `bool` | public | - |
| `id` | `string` | public | - |
| `trainCrewId` | `string` | public | - |
| `DefinitionInfo` | `TypedContainerItem<CarDefinition>` | public | - |
| `nominalBrakingForce` | `float` | private | - |
| `Config` | `Config` | protected | - |
| `SetupDiagnostics` | `StringDiagnosticCollector` | internal | `readonly` |
| `BrakeForceMultiplier` | `float` | public | `static` |
| `BrakeForceMultiplierHandbrake` | `float` | public | `static` |
| `WearFeature` | `bool` | public | `static` |
| `OilFeature` | `bool` | public | `static` |
| `OverhaulMiles` | `int` | public | `static` |
| `WearMultiplier` | `float` | public | `static` |
| `OilUseMultiplier` | `float` | public | `static` |
| `EndGearF` | `EndGear` | private | - |
| `EndGearR` | `EndGear` | private | - |
| `LocationF` | `Location` | public | - |
| `LocationR` | `Location` | public | - |
| `wheelInsetF` | `float` | public | - |
| `wheelInsetR` | `float` | public | - |
| `WheelBoundsF` | `Location` | public | - |
| `WheelBoundsR` | `Location` | public | - |
| `FrontIsA` | `bool` | public | - |
| `LastBodyPosition` | `Vector3[]` | public | `readonly` |
| `truckSeparation` | `float` | public | - |
| `carLength` | `float` | public | - |
| `couplerHeight` | `float` | public | - |
| `airHosePosition` | `Vector3` | public | - |
| `_truckA` | `Wheelset` | private | - |
| `_truckB` | `Wheelset` | private | - |
| `_audioReparenter` | `AudioReparenter` | private | - |
| `_mover` | `CarMover` | internal | - |
| `_rollingPlayer` | `RollingPlayer` | protected | - |
| `BodyTransform` | `Transform` | public | - |
| `_moverPositionWheelBoundsF` | `Location` | private | - |
| `_modelLoadPending` | `bool` | private | - |
| `_bodyRenderers` | `Renderer[]` | private | - |
| `_isVisible` | `bool` | private | - |
| `_hasReceivedDistanceBand` | `bool` | private | - |
| `_enablePositionCouplers` | `bool` | private | - |
| `_ownedMaterials` | `List<Material>` | private | `readonly` |
| `_truckRenderers` | `List<Renderer>` | private | `readonly` |
| `_velocity` | `float` | private | - |
| `_set` | `IntegrationSet` | private | - |
| `compensatingAcceleration` | `float` | public | - |
| `air` | `CarAirSystem` | public | - |
| `_airFlowAudioClip` | `AudioClip` | private | - |
| `_brakeExhaustAudioSource` | `IAudioSource` | private | - |
| `_grade` | `float` | private | - |
| `_loadWeight` | `float` | private | - |
| `maxSpeedMph` | `float` | public | - |
| `_curvatureRetardingForce` | `float` | private | - |
| `_isFirstPosition` | `bool` | protected | - |
| `ghost` | `bool` | public | - |
| `KeyValueObject` | `KeyValueObject` | public | - |
| `Observers` | `HashSet<IDisposable>` | protected | `readonly` |
| `_controlProperties` | `CarControlProperties` | private | - |
| `_willDestroyCalled` | `bool` | private | - |
| `_controlObservers` | `HashSet<IDisposable>` | protected | `readonly` |
| `_movementListeners` | `List<ICarMovementListener>` | private | `readonly` |
| `_lastOnPosition` | `Vector3` | private | - |
| `_lastBrakeCylinderPressure` | `float` | private | - |
| `MapIcon` | `MapIcon` | protected | - |
| `TagCallout` | `TagCallout` | public | - |
| `BrakeAnimators` | `HashSet<IBrakeAnimator>` | protected | `readonly` |
| `_modelLoadTokens` | `HashSet<CarModelLoadToken>` | private | `readonly` |
| `_truckPrefabLoadTask` | `Task<Wheelset>` | private | - |
| `_lastCurvatureUpdate` | `float` | private | - |
| `CurvatureUpdatePeriod` | `float` | private | `const` |
| `_condition` | `float` | private | - |
| `debugCondition` | `bool` | public | - |
| `_conditionDebugSetup` | `bool` | private | - |
| `_conditionUpdateCoroutine` | `Coroutine` | private | - |
| `_hotbox` | `float` | private | - |
| `_derailment` | `float` | private | - |
| `_derailmentDisplay` | `float` | private | - |
| `_derailmentUpdateCoroutine` | `Coroutine` | private | - |
| `_oiled` | `float` | private | - |
| `MaxOilingSpeedMph` | `float` | public | `const` |
| `_unbankedOdometerService` | `float` | private | - |
| `_unbankedOdometerActual` | `float` | private | - |
| `KeyOdometerActual` | `string` | private | `const` |
| `KeyOdometerService` | `string` | private | `const` |
| `KeyLastOverhaul` | `string` | private | `const` |
| `KeyOverhaulProgress` | `string` | private | `const` |
| `CouplerSeparation` | `float` | public | `const` |
| `RollingResistance` | `float` | internal | `const` |
| `CouplerStretch` | `float` | internal | `const` |
| `_setupPrefabs` | `SetupPrefabs` | protected | - |
| `_delayedUnload` | `Coroutine` | private | - |
| `KeyOiled` | `string` | internal | `const` |
| `_oilPointPickables` | `List<GameObject>` | private | `readonly` |
| `swayPosition` | `float` | private | - |
| `swayVelocity` | `float` | private | - |
| `swayCurveForce` | `float` | private | - |
| `swayNoiseForce` | `float` | private | - |
| `_swayComponentSpeed` | `float` | private | - |
| `_swayMassCoeff` | `float` | private | - |
| `_linearOffset` | `float` | protected | - |
| `KeyOwned` | `string` | public | `const` |
| `KeyOpsPassengerMarker` | `string` | public | `const` |
| `KeyOpsRepairDestination` | `string` | public | `const` |
| `KeyOpsSellDestination` | `string` | public | `const` |
| `KeyOpsWaybill` | `string` | public | `const` |
| `KeyHotbox` | `string` | public | `const` |
| `DefinitionIdentifier` | `string` | protected | - |
| `IsInBardo` | `bool` | public | - |
| `Definition` | `CarDefinition` | public | - |
| `CarType` | `string` | public | - |
| `OpsLocation` | `Location` | public | - |
| `VelocityMphAbs` | `float` | public | - |
| `Weight` | `float` | public | - |
| `TractiveForce` | `float` | public | - |
| `Orientation` | `float` | public | - |
| `ControlProperties` | `CarControlProperties` | public | - |
| `Archetype` | `CarArchetype` | public | - |
| `TrainController` | `TrainController` | private | `static` |
| `Graph` | `Graph` | private | `static` |
| `EnableCondition` | `bool` | public | - |
| `HasHotbox` | `bool` | public | - |
| `IsDerailed` | `bool` | public | - |
| `Oiled` | `float` | public | - |
| `InitialTagCalloutPosition` | `Vector3` | public | - |
| `SnapshotLocation` | `Location` | public | - |
| `IsOwnedByPlayer` | `bool` | public | - |

