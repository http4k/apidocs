[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SwitchTrigger](./index.md)

# SwitchTrigger

`class SwitchTrigger : `[`ChaosTrigger`](../-chaos-trigger.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L101)

Simple toggleable trigger to turn ChaosBehaviour on/off

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SwitchTrigger(initialPosition: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)`<br>Simple toggleable trigger to turn ChaosBehaviour on/off |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isActive](is-active.md) | `fun isActive(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toggle](toggle.md) | `fun toggle(newValue: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../kotlin.-function1/and.md) | `infix fun `[`ChaosTrigger`](../-chaos-trigger.md)`.and(that: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosTrigger`](../-chaos-trigger.md) |
| [not](../kotlin.-function1/not.md) | `operator fun `[`ChaosTrigger`](../-chaos-trigger.md)`.not(): (`[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](../kotlin.-function1/or.md) | `infix fun `[`ChaosTrigger`](../-chaos-trigger.md)`.or(that: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosTrigger`](../-chaos-trigger.md) |
