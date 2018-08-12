[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStages](./index.md)

# ChaosStages

`object ChaosStages` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L56)

### Types

| Name | Summary |
|---|---|
| [Wait](-wait/index.md) | `object Wait : `[`ChaosStage`](../-chaos-stage.md)<br>Does not apply any ChaosBehaviour. |

### Functions

| Name | Summary |
|---|---|
| [Repeat](-repeat.md) | `fun Repeat(newStageFn: () -> `[`ChaosStage`](../-chaos-stage.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL, the stage function will be fired on each iteration and expecting a NEW instance. |
