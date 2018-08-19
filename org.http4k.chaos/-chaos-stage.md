[http4k](../index.md) / [org.http4k.chaos](index.md) / [ChaosStage](./-chaos-stage.md)

# ChaosStage

`typealias ChaosStage = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L18)

Defines a periodic element during which a particular ChaosBehaviour is active.

### Inheritors

| Name | Summary |
|---|---|
| [Variable](-chaos-stages/-variable/index.md) | `class Variable : `[`ChaosStage`](./-chaos-stage.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |
| [Wait](-chaos-stages/-wait/index.md) | `object Wait : `[`ChaosStage`](./-chaos-stage.md)<br>Does not apply any ChaosBehaviour. |
