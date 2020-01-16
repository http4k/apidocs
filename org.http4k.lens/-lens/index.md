[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Lens](./index.md)

# Lens

`open class Lens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`IN`](index.md#IN)`, `[`FINAL`](index.md#FINAL)`>, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Meta`](../-meta/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lens.kt#L6)

A Lens provides the uni-directional extraction of an entity from a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Lens(meta: `[`Meta`](../-meta/index.md)`, lensGet: (`[`IN`](index.md#IN)`) -> `[`FINAL`](index.md#FINAL)`)`<br>A Lens provides the uni-directional extraction of an entity from a target. |

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `val meta: `[`Meta`](../-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open operator fun invoke(target: `[`IN`](index.md#IN)`): `[`FINAL`](index.md#FINAL)<br>Lens operation to get the value from the target |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../-meta/index.md)`>` |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../-lens-extractor/index.md#IN)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../-lens-extractor/index.md#IN)`> get(target: `[`R`](../-lens-extractor/get.md#R)`): `[`OUT`](../-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.chaos/kotlin.-function1/and.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.and(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [asFilter](../../org.http4k.chaos/kotlin.-function1/as-filter.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.asFilter(): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [asK8sServer](../../org.http4k.cloudnative/kotlin.-function1/as-k8s-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, healthApp: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = Health(), healthPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8001): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md)<br>`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, env: `[`Environment`](../../org.http4k.cloudnative.env/-environment/index.md)` = ENV, healthApp: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = Health()): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md) |
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(fn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)<br>`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [not](../../org.http4k.chaos/kotlin.-function1/not.md) | `operator fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.not(): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](../../org.http4k.chaos/kotlin.-function1/or.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.or(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [renderToResponse](../../org.http4k.template/kotlin.-function1/render-to-response.md) | `fun `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`.renderToResponse(viewModel: `[`ViewModel`](../../org.http4k.template/-view-model/index.md)`, status: `[`Status`](../../org.http4k.core/-status/index.md)` = OK, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)` = TEXT_HTML): `[`Response`](../../org.http4k.core/-response/index.md)<br>Convenience method for generating a Response from a view model. |
| [testWsClient](../../org.http4k.testing/kotlin.-function1/test-ws-client.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.testWsClient(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
| [then](../../org.http4k.events/kotlin.-function1/then.md) | `fun `[`Events`](../../org.http4k.events/-events.md)`.then(next: `[`Events`](../../org.http4k.events/-events.md)`): `[`Events`](../../org.http4k.events/-events.md) |
| [then](../../org.http4k.template/kotlin.-function1/then.md) | `fun `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`.then(that: `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`): `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)<br>Compose a TemplateRenderer with another, so you can fall back. |
| [then](../../org.http4k.chaos/kotlin.-function1/then.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.then(nextStage: `[`Stage`](../../org.http4k.chaos/-stage.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../../org.http4k.chaos/kotlin.-function1/until.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.until(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosControls](../../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.~~withChaosControls~~(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = ChaosStages.Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [withChaosEngine](../../org.http4k.chaos/kotlin.-function1/with-chaos-engine.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosEngine(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiLens](../-bi-di-lens/index.md) | `class BiDiLens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](../-bi-di-lens/index.md#FINAL)`, `[`IN`](../-bi-di-lens/index.md#IN)`>, `[`Lens`](./index.md)`<`[`IN`](../-bi-di-lens/index.md#IN)`, `[`FINAL`](../-bi-di-lens/index.md#FINAL)`>`<br>A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target. |
| [Mapping](../../org.http4k.jsonrpc/-mapping/index.md) | `class Mapping<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`Lens`](./index.md)`<`[`IN`](../../org.http4k.jsonrpc/-mapping/index.md#IN)`, `[`OUT`](../../org.http4k.jsonrpc/-mapping/index.md#OUT)`>` |
| [PathLens](../-path-lens/index.md) | `open class PathLens<out FINAL> : `[`Lens`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`FINAL`](../-path-lens/index.md#FINAL)`>` |
