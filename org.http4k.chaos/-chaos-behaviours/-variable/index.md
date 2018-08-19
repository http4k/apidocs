[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [Variable](./index.md)

# Variable

`class Variable : `[`ChaosBehaviour`](../../-chaos-behaviour.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L125)

Provide a means of modifying a ChaosBehaviour at runtime.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Variable(current: `[`ChaosBehaviour`](../../-chaos-behaviour.md)` = None)`<br>Provide a means of modifying a ChaosBehaviour at runtime. |

### Properties

| Name | Summary |
|---|---|
| [current](current.md) | `var current: `[`ChaosBehaviour`](../../-chaos-behaviour.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../../org.http4k.core/-response/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
