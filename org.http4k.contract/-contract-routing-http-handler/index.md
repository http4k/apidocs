[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](./index.md)

# ContractRoutingHttpHandler

`data class ContractRoutingHttpHandler : `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ContractRoutingHttpHandler(renderer: `[`ContractRenderer`](../-contract-renderer/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?, descriptionSecurity: `[`Security`](../../org.http4k.contract.security/-security/index.md)`?, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, preFlightExtraction: `[`PreFlightExtraction`](../-pre-flight-extraction/index.md)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../-contract-route/index.md)`> = emptyList(), rootAsString: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", preSecurityFilter: `[`Filter`](../../org.http4k.core/-filter.md)` = Filter.NoOp, postSecurityFilter: `[`Filter`](../../org.http4k.core/-filter.md)` = Filter.NoOp, includeDescriptionRoute: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [match](match.md) | Attempt to supply an HttpHandler which can service the passed request.`fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`RouterMatch`](../../org.http4k.routing/-router-match/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [withBasePath](with-base-path.md) | Returns a Router which prepends the passed base path to the logic determining the match().`fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRoutingHttpHandler`](./index.md) |
| [withFilter](with-filter.md) | NOTE: By default, filters for Contracts are applied *before* the Security filter. Use withPostSecurityFilter() to achieve population of filters after security.`fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`ContractRoutingHttpHandler`](./index.md) |
| [withPostSecurityFilter](with-post-security-filter.md) | `fun withPostSecurityFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`ContractRoutingHttpHandler`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.routing/and.md) | `infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.and(that: `[`Router`](../../org.http4k.routing/-router/index.md)`): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [bind](../../org.http4k.routing/bind.md) | `infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.bind(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>`infix fun `[`Router`](../../org.http4k.routing/-router/index.md)`.bind(handler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
