[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](./index.md)

# ChaosEngine

`class ChaosEngine : `[`Filter`](../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L15)

The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a
standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine
is deactivated, so activate() needs to be called to witness any change in behaviour,

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ChaosEngine(behaviour: `[`Behaviour`](../-behaviour.md)`)``ChaosEngine(initialStage: `[`Stage`](../-stage.md)` = Wait)`<br>The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour, |

### Functions

| Name | Summary |
|---|---|
| [disable](disable.md) | `fun disable(): `[`ChaosEngine`](./index.md)<br>Turn off Chaos Engine. No Chaotic behaviour will be applied. |
| [enable](enable.md) | `fun enable(): `[`ChaosEngine`](./index.md)<br>Turn on Chaos Engine using the pre-initialised chaotic behaviour. Note that this may not actually produce any effect based on the configured behaviour (e.g. if there is a specific Trigger that is condition-based.)`fun enable(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`ChaosEngine`](./index.md)<br>Update with new simple Chaotic behaviour to be applied whenever the ChaosEngine is enabled.`fun enable(stage: `[`Stage`](../-stage.md)`): `[`ChaosEngine`](./index.md)<br>Update the new complex (multi-stage, triggers etc) Chaotic behaviour to be applied whenever the ChaosEngine is enabled. |
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [isEnabled](is-enabled.md) | `fun isEnabled(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if the configured Chaos behaviour is currently being applied to all traffic. |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Outputs description of the current state. |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../applied-when.md) | `fun `[`Behaviour`](../-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../-trigger.md)`): `[`Stage`](../-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
