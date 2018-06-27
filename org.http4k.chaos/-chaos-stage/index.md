[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStage](./index.md)

# ChaosStage

`interface ChaosStage` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStage.kt#L14)

Defines a periodic element during which a particular ChaosBehaviour is active.

### Types

| Name | Summary |
|---|---|
| [Wait](-wait/index.md) | `object Wait : `[`ChaosStage`](./index.md)<br>Does not apply any ChaosBehaviour. |

### Functions

| Name | Summary |
|---|---|
| [asFilter](as-filter.md) | `open fun asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [invoke](invoke.md) | `abstract operator fun invoke(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)`?` |
| [then](then.md) | `open fun then(nextStage: `[`ChaosStage`](./index.md)`): `[`ChaosStage`](./index.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `open fun until(stageTrigger: `[`ChaosStageTrigger`](../-chaos-stage-trigger.md)`): `[`ChaosStage`](./index.md)<br>Stop applying the ChaosBehaviour of this stage when the StageTrigger fires. |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Repeat](-repeat.md) | `fun Repeat(newStageFn: () -> `[`ChaosStage`](./index.md)`): `[`ChaosStage`](./index.md)<br>Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL, the stage function will be fired on each iteration and expecting a NEW instance. |

### Inheritors

| Name | Summary |
|---|---|
| [Wait](-wait/index.md) | `object Wait : `[`ChaosStage`](./index.md)<br>Does not apply any ChaosBehaviour. |
