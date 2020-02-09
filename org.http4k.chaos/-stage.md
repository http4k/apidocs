[http4k](../index.md) / [org.http4k.chaos](index.md) / [Stage](./-stage.md)

# Stage

`typealias Stage = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Filter`](../org.http4k.core/-filter/index.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L17)

Defines a periodic element during which a particular ChaosBehaviour is active.

### Inheritors

| Name | Summary |
|---|---|
| [Variable](-chaos-stages/-variable/index.md) | `class Variable : `[`Stage`](./-stage.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |
| [Wait](-chaos-stages/-wait/index.md) | `object Wait : `[`Stage`](./-stage.md)<br>Does not apply any ChaosBehaviour. |
