[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](./index.md)

# ChaosEngine

`class ChaosEngine : `[`Filter`](../../org.http4k.core/-filter.md)

The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a
standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine
is deactivated, so activate() needs to be called to witness any change in behaviour,

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ChaosEngine(behaviour: `[`Behaviour`](../-behaviour.md)`)`<br>The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour,`ChaosEngine(initialStage: `[`Stage`](../-stage.md)` = Wait)` |

### Functions

| Name | Summary |
|---|---|
| [disable](disable.md) | Turn off Chaos Engine. No Chaotic behaviour will be applied.`fun disable(): `[`ChaosEngine`](./index.md) |
| [enable](enable.md) | Turn on Chaos Engine using the pre-initialised chaotic behaviour. Note that this may not actually produce any effect based on the configured behaviour (e.g. if there is a specific Trigger that is condition-based.)`fun enable(): `[`ChaosEngine`](./index.md)<br>Update with new simple Chaotic behaviour to be applied whenever the ChaosEngine is enabled.`fun enable(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`ChaosEngine`](./index.md)<br>Update the new complex (multi-stage, triggers etc) Chaotic behaviour to be applied whenever the ChaosEngine is enabled.`fun enable(stage: `[`Stage`](../-stage.md)`): `[`ChaosEngine`](./index.md) |
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [isEnabled](is-enabled.md) | Check if the configured Chaos behaviour is currently being applied to all traffic.`fun isEnabled(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | Outputs description of the current state.`fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../applied-when.md) | `fun `[`Behaviour`](../-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../-trigger.md)`): `[`Stage`](../-stage.md) |
| [inIntelliJOnly](../../org.http4k.filter/in-intelli-j-only.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.inIntelliJOnly(): `[`Filter`](../../org.http4k.core/-filter.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`Filter`](../../org.http4k.core/-filter.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [then](../../org.http4k.serverless/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)`): `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoaderWithContexts`](../../org.http4k.serverless/-app-loader-with-contexts.md)`): <ERROR CLASS>` |
