[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SwitchTrigger](./index.md)

# SwitchTrigger

`class SwitchTrigger : `[`ChaosTrigger`](../-chaos-trigger.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L28)

Simple toggleable trigger to turn ChaosBehaviour on/off

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SwitchTrigger(initialPosition: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)`<br>Simple toggleable trigger to turn ChaosBehaviour on/off |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toggle](toggle.md) | `fun toggle(newValue: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
