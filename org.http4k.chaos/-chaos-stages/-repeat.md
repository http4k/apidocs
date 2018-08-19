[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStages](index.md) / [Repeat](./-repeat.md)

# Repeat

`fun Repeat(newStageFn: () -> `[`ChaosStage`](../-chaos-stage.md)`): `[`ChaosStage`](../-chaos-stage.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L65)

Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL,
the stage function will be fired on each iteration and expecting a NEW instance.

