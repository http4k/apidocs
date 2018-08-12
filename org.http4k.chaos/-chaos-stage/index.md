[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStage](./index.md)

# ChaosStage

`interface ChaosStage` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L14)

Defines a periodic element during which a particular ChaosBehaviour is active.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [asFilter](../as-filter.md) | `fun `[`ChaosStage`](./index.md)`.asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [then](../then.md) | `fun `[`ChaosStage`](./index.md)`.then(nextStage: `[`ChaosStage`](./index.md)`): `[`ChaosStage`](./index.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../until.md) | `fun `[`ChaosStage`](./index.md)`.until(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosStage`](./index.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |

### Inheritors

| Name | Summary |
|---|---|
| [Wait](../-chaos-stages/-wait/index.md) | `object Wait : `[`ChaosStage`](./index.md)<br>Does not apply any ChaosBehaviour. |
