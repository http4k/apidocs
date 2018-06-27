[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStage](index.md) / [Repeat](./-repeat.md)

# Repeat

`fun Repeat(stageFn: () -> `[`ChaosStage`](index.md)`): `[`ChaosStage`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStage.kt#L22)

Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL,
the stage function will be fired on each iteration and expecting a NEW instance.

