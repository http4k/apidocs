[http4k](../index.md) / [org.http4k.contract](./index.md)

## Package org.http4k.contract

Code for defining typesafe HTTP contracts. Contains subpackages for OpenAPI v2 and v3

### Types

| Name | Summary |
|---|---|
| [ApiInfo](-api-info.md) | `typealias ~~ApiInfo~~ = `[`ApiInfo`](../org.http4k.contract.openapi/-api-info/index.md) |
| [ApiKey](-api-key.md) | `typealias ~~ApiKey~~<T> = `[`ApiKeySecurity`](../org.http4k.contract.security/-api-key-security/index.md)`<T>` |
| [ApiKeySecurity](-api-key-security.md) | `typealias ~~ApiKeySecurity~~<T> = `[`ApiKeySecurity`](../org.http4k.contract.security/-api-key-security/index.md)`<T>` |
| [BasicAuthSecurity](-basic-auth-security.md) | `typealias ~~BasicAuthSecurity~~ = `[`BasicAuthSecurity`](../org.http4k.contract.security/-basic-auth-security/index.md) |
| [ContractBuilder](-contract-builder/index.md) | `class ContractBuilder` |
| [ContractRenderer](-contract-renderer/index.md) | `interface ContractRenderer : `[`ErrorResponseRenderer`](-error-response-renderer/index.md) |
| [ContractRoute](-contract-route/index.md) | `class ContractRoute : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ContractRouteSpec](-contract-route-spec/index.md) | `abstract class ContractRouteSpec` |
| [ContractRouteSpec0](-contract-route-spec0/index.md) | `class ContractRouteSpec0 : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec1](-contract-route-spec1/index.md) | `class ContractRouteSpec1<out A> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec10](-contract-route-spec10/index.md) | `class ContractRouteSpec10<out A, out B, out C, out D, out E, out F, out G, out H, out I, out J> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec2](-contract-route-spec2/index.md) | `class ContractRouteSpec2<out A, out B> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec3](-contract-route-spec3/index.md) | `class ContractRouteSpec3<out A, out B, out C> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec4](-contract-route-spec4/index.md) | `class ContractRouteSpec4<out A, out B, out C, out D> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec5](-contract-route-spec5/index.md) | `class ContractRouteSpec5<out A, out B, out C, out D, out E> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec6](-contract-route-spec6/index.md) | `class ContractRouteSpec6<out A, out B, out C, out D, out E, out F> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec7](-contract-route-spec7/index.md) | `class ContractRouteSpec7<out A, out B, out C, out D, out E, out F, out G> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec8](-contract-route-spec8/index.md) | `class ContractRouteSpec8<out A, out B, out C, out D, out E, out F, out G, out H> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRouteSpec9](-contract-route-spec9/index.md) | `class ContractRouteSpec9<out A, out B, out C, out D, out E, out F, out G, out H, out I> : `[`ContractRouteSpec`](-contract-route-spec/index.md) |
| [ContractRoutingHttpHandler](-contract-routing-http-handler/index.md) | `data class ContractRoutingHttpHandler : `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
| [ErrorResponseRenderer](-error-response-renderer/index.md) | `interface ErrorResponseRenderer` |
| [HttpMessageMeta](-http-message-meta/index.md) | `open class HttpMessageMeta<out T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>` |
| [JsonErrorResponseRenderer](-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<NODE> : `[`ErrorResponseRenderer`](-error-response-renderer/index.md) |
| [NoRenderer](-no-renderer/index.md) | `object NoRenderer : `[`ContractRenderer`](-contract-renderer/index.md) |
| [NoSecurity](-no-security.md) | `typealias ~~NoSecurity~~ = `[`NoSecurity`](../org.http4k.contract.security/-no-security/index.md) |
| [OpenApi](-open-api.md) | `typealias ~~OpenApi~~<NODE> = `[`OpenApi2`](../org.http4k.contract.openapi.v2/-open-api2/index.md)`<NODE>` |
| [PathSegments](-path-segments/index.md) | `sealed class PathSegments` |
| [PreFlightExtraction](-pre-flight-extraction/index.md) | Determines which parts of the request should be pre-extracted to check for presence before being passed to the ultimate HttpHandler for this route. Choice will be determined by two competing scenarios:`interface PreFlightExtraction : (`[`RouteMeta`](-route-meta/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../org.http4k.core/-request/index.md)`, *>>` |
| [RequestMeta](-request-meta/index.md) | `class RequestMeta : `[`HttpMessageMeta`](-http-message-meta/index.md)`<`[`Request`](../org.http4k.core/-request/index.md)`>` |
| [ResponseMeta](-response-meta/index.md) | `class ResponseMeta : `[`HttpMessageMeta`](-http-message-meta/index.md)`<`[`Response`](../org.http4k.core/-response/index.md)`>` |
| [Root](-root/index.md) | `object Root : `[`PathSegments`](-path-segments/index.md) |
| [RouteMeta](-route-meta/index.md) | `data class RouteMeta` |
| [RouteMetaDsl](-route-meta-dsl/index.md) | `class RouteMetaDsl` |
| [Security](-security.md) | `typealias ~~Security~~ = `[`Security`](../org.http4k.contract.security/-security/index.md) |
| [SimpleJson](-simple-json.md) | `typealias ~~SimpleJson~~<NODE> = `[`SimpleJson`](../org.http4k.contract.simple/-simple-json/index.md)`<NODE>` |
| [Slash](-slash/index.md) | `data class Slash : `[`PathSegments`](-path-segments/index.md) |
| [Tag](-tag/index.md) | `data class Tag` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [bindContract](bind-contract.md) | `infix fun <A> `[`PathLens`](../org.http4k.lens/-path-lens/index.md)`<A>.bindContract(method: `[`Method`](../org.http4k.core/-method/index.md)`): Binder<A>` |
| [contract](contract.md) | `fun ~~contract~~(vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)<br>`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)<br>`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)<br>`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)` = NoRenderer, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", security: `[`Security`](../org.http4k.contract.security/-security/index.md)` = NoSecurity, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)<br>`fun contract(fn: `[`ContractBuilder`](-contract-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) |
| [div](div.md) | `operator fun <A> `[`PathLens`](../org.http4k.lens/-path-lens/index.md)`<A>.div(next: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRouteSpec2`](-contract-route-spec2/index.md)`<A, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>`operator fun <A, B> `[`PathLens`](../org.http4k.lens/-path-lens/index.md)`<A>.div(next: `[`PathLens`](../org.http4k.lens/-path-lens/index.md)`<B>): `[`ContractRouteSpec2`](-contract-route-spec2/index.md)`<A, B>` |
| [meta](meta.md) | `infix fun <A> `[`PathLens`](../org.http4k.lens/-path-lens/index.md)`<A>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](-contract-route-spec1/index.md)`<A>`<br>`infix fun `[`ContractRouteSpec0`](-contract-route-spec0/index.md)`.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec0`](-contract-route-spec0/index.md)<br>`infix fun <A> `[`ContractRouteSpec1`](-contract-route-spec1/index.md)`<A>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec1`](-contract-route-spec1/index.md)`<A>`<br>`infix fun <A, B> `[`ContractRouteSpec2`](-contract-route-spec2/index.md)`<A, B>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec2`](-contract-route-spec2/index.md)`<A, B>`<br>`infix fun <A, B, C> `[`ContractRouteSpec3`](-contract-route-spec3/index.md)`<A, B, C>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec3`](-contract-route-spec3/index.md)`<A, B, C>`<br>`infix fun <A, B, C, D> `[`ContractRouteSpec4`](-contract-route-spec4/index.md)`<A, B, C, D>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec4`](-contract-route-spec4/index.md)`<A, B, C, D>`<br>`infix fun <A, B, C, D, E> `[`ContractRouteSpec5`](-contract-route-spec5/index.md)`<A, B, C, D, E>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec5`](-contract-route-spec5/index.md)`<A, B, C, D, E>`<br>`infix fun <A, B, C, D, E, F> `[`ContractRouteSpec6`](-contract-route-spec6/index.md)`<A, B, C, D, E, F>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec6`](-contract-route-spec6/index.md)`<A, B, C, D, E, F>`<br>`infix fun <A, B, C, D, E, F, G> `[`ContractRouteSpec7`](-contract-route-spec7/index.md)`<A, B, C, D, E, F, G>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec7`](-contract-route-spec7/index.md)`<A, B, C, D, E, F, G>`<br>`infix fun <A, B, C, D, E, F, G, H> `[`ContractRouteSpec8`](-contract-route-spec8/index.md)`<A, B, C, D, E, F, G, H>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec8`](-contract-route-spec8/index.md)`<A, B, C, D, E, F, G, H>`<br>`infix fun <A, B, C, D, E, F, G, H, I> `[`ContractRouteSpec9`](-contract-route-spec9/index.md)`<A, B, C, D, E, F, G, H, I>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec9`](-contract-route-spec9/index.md)`<A, B, C, D, E, F, G, H, I>`<br>`infix fun <A, B, C, D, E, F, G, H, I, J> `[`ContractRouteSpec10`](-contract-route-spec10/index.md)`<A, B, C, D, E, F, G, H, I, J>.meta(new: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRouteSpec10`](-contract-route-spec10/index.md)`<A, B, C, D, E, F, G, H, I, J>` |
| [routeMetaDsl](route-meta-dsl.md) | `fun routeMetaDsl(fn: `[`RouteMetaDsl`](-route-meta-dsl/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = {}): `[`RouteMeta`](-route-meta/index.md) |
