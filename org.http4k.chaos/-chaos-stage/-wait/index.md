[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosStage](../index.md) / [Wait](./index.md)

# Wait

`object Wait : `[`ChaosStage`](../index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStage.kt#L35)

Does not apply any ChaosBehaviour.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../../org.http4k.core/-response/index.md)`?` |

### Inherited Functions

| Name | Summary |
|---|---|
| [asFilter](../as-filter.md) | `open fun asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [then](../then.md) | `open fun then(next: `[`ChaosStage`](../index.md)`): `[`ChaosStage`](../index.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../until.md) | `open fun until(trigger: `[`StageTrigger`](../../-stage-trigger.md)`): `[`ChaosStage`](../index.md)<br>Stop applying the ChaosBehaviour of this stage when the StageTrigger fires. |
