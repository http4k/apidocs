[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SwitchTrigger](./index.md)

# SwitchTrigger

`class SwitchTrigger : `[`Trigger`](../-trigger.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L168)

Simple toggleable trigger to turn ChaosBehaviour on/off

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SwitchTrigger(initialPosition: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)`<br>Simple toggleable trigger to turn ChaosBehaviour on/off |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(req: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isActive](is-active.md) | `fun isActive(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toggle](toggle.md) | `fun toggle(newValue: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../kotlin.-function1/and.md) | `infix fun `[`Trigger`](../-trigger.md)`.and(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
| [not](../kotlin.-function1/not.md) | `operator fun `[`Trigger`](../-trigger.md)`.not(): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](../kotlin.-function1/or.md) | `infix fun `[`Trigger`](../-trigger.md)`.or(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
