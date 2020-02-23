[http4k](../index.md) / [org.http4k.chaos](./index.md)

## Package org.http4k.chaos

### Types

| Name | Summary |
|---|---|
| [Behaviour](-behaviour.md) | Encapsulates the type of bad behaviour to apply to the response.`typealias Behaviour = `[`Filter`](../org.http4k.core/-filter/index.md) |
| [ChaosBehaviours](-chaos-behaviours/index.md) | `object ChaosBehaviours` |
| [ChaosEngine](-chaos-engine/index.md) | The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour,`class ChaosEngine : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [ChaosStages](-chaos-stages/index.md) | `object ChaosStages` |
| [ChaosTriggers](-chaos-triggers/index.md) | `object ChaosTriggers` |
| [RemoteChaosApi](-remote-chaos-api/index.md) | A set of endpoints to an application which will control the setting and toggling chaos behaviour. The added endpoints are: GET //status &lt;- check the on off/status of the injected chaos POST //activate &lt;- turn on the chaos. optionally POST a JSON body to set a list of new stages to use. POST //deactivate &lt;- turn off the chaos POST //toggle &lt;- toggle the chaos`object RemoteChaosApi` |
| [Stage](-stage.md) | Defines a periodic element during which a particular ChaosBehaviour is active.`typealias Stage = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Filter`](../org.http4k.core/-filter/index.md)`?` |
| [Trigger](-trigger.md) | `typealias Trigger = (req: `[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.fasterxml.jackson.databind.JsonNode](com.fasterxml.jackson.databind.-json-node/index.md) |  |
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [appliedWhen](applied-when.md) | `fun `[`Behaviour`](-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](-trigger.md)`): `[`Stage`](-stage.md) |
| [withChaosApi](with-chaos-api.md) | Mixin the set of remote Chaos API endpoints to a standard HttpHandler, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls.`fun `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`.withChaosApi(engine: `[`ChaosEngine`](-chaos-engine/index.md)` = ChaosEngine(), security: `[`Security`](../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
| [withChaosControls](with-chaos-controls.md) | `fun `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`.~~withChaosControls~~(stage: `[`Stage`](-stage.md)` = ChaosStages.Wait, security: `[`Security`](../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
