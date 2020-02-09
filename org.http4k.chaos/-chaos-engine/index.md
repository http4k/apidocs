[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](./index.md)

# ChaosEngine

`class ChaosEngine : `[`Filter`](../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L14)

The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a
standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ChaosEngine(behaviour: `[`Behaviour`](../-behaviour.md)`, alreadyActivated: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true)``ChaosEngine(initialStage: `[`Stage`](../-stage.md)` = Wait, alreadyActivated: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true)`<br>The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [isActive](is-active.md) | `fun isActive(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if the configured Chaos behaviour is currently being applied to all traffic. |
| [toggle](toggle.md) | `fun toggle(isActive: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Toggle the behaviour on/off. |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Outputs description of the current state. |
| [update](update.md) | `fun update(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Update the new simple Chaotic behaviour to be applied when the ChaosEngine is enabled.`fun update(stage: `[`Stage`](../-stage.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Update the new complex (multi-stage, triggers etc) Chaotic behaviour to be applied when the ChaosEngine is enabled. |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../applied-when.md) | `fun `[`Behaviour`](../-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../-trigger.md)`): `[`Stage`](../-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
