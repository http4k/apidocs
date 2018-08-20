[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [Variable](./index.md)

# Variable

`class Variable : `[`Behaviour`](../../-behaviour.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L166)

Provide a means of modifying a ChaosBehaviour at runtime.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Variable(current: `[`Behaviour`](../../-behaviour.md)` = None())`<br>Provide a means of modifying a ChaosBehaviour at runtime. |

### Properties

| Name | Summary |
|---|---|
| [current](current.md) | `var current: `[`Behaviour`](../../-behaviour.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../../org.http4k.core/-http-handler.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
