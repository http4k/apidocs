[http4k](../index.md) / [org.http4k.chaos](index.md) / [Stage](./-stage.md)

# Stage

`interface Stage : (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Filter`](../org.http4k.core/-filter/index.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L19)

Defines a periodic element during which a particular ChaosBehaviour is active.

### Extension Functions

| Name | Summary |
|---|---|
| [asFilter](as-filter.md) | `fun `[`Stage`](./-stage.md)`.asFilter(): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [then](then.md) | `fun `[`Stage`](./-stage.md)`.then(nextStage: `[`Stage`](./-stage.md)`): `[`Stage`](./-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `fun `[`Stage`](./-stage.md)`.until(trigger: `[`Trigger`](-trigger.md)`): `[`Stage`](./-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |

### Inheritors

| Name | Summary |
|---|---|
| [Variable](-chaos-stages/-variable/index.md) | `class Variable : `[`Stage`](./-stage.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |
| [Wait](-chaos-stages/-wait/index.md) | `object Wait : `[`Stage`](./-stage.md)<br>Does not apply any ChaosBehaviour. |
