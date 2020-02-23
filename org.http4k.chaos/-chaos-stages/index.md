[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosStages](./index.md)

# ChaosStages

`object ChaosStages`

### Types

| Name | Summary |
|---|---|
| [Variable](-variable/index.md) | Provide a means of modifying a ChaosBehaviour at runtime.`class Variable : `[`Stage`](../-stage.md) |
| [Wait](-wait/index.md) | Does not apply any ChaosBehaviour.`object Wait : `[`Stage`](../-stage.md) |

### Functions

| Name | Summary |
|---|---|
| [Repeat](-repeat.md) | Repeats a stage (or composite stage in repeating pattern). Since ChaosStages are STATEFUL, the stage function will be fired on each iteration and expecting a NEW instance.`fun Repeat(newStageFn: () -> `[`Stage`](../-stage.md)`): `[`Stage`](../-stage.md) |
