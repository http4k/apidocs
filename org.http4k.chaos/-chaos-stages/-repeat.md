[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStages](index.md) / [Repeat](./-repeat.md)

# Repeat

`fun Repeat(newStageFn: () -> `[`Stage`](../-stage.md)`): `[`Stage`](../-stage.md)

Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL,
the stage function will be fired on each iteration and expecting a NEW instance.

