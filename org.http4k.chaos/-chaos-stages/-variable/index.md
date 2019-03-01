[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosStages](../index.md) / [Variable](./index.md)

# Variable

`class Variable : `[`Stage`](../../-stage.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosStages.kt#L79)

Provide a means of modifying a ChaosBehaviour at runtime.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Variable(current: `[`Stage`](../../-stage.md)` = None().appliedWhen(Always()))`<br>Provide a means of modifying a ChaosBehaviour at runtime. |

### Properties

| Name | Summary |
|---|---|
| [current](current.md) | `var current: `[`Stage`](../../-stage.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../../org.http4k.core/-request/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)`?` |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
