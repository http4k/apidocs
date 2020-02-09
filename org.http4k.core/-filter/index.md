[http4k](../../index.md) / [org.http4k.core](../index.md) / [Filter](./index.md)

# Filter

`interface Filter : (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Http4k.kt#L7)

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`HttpHandler`](../-http-handler.md)`) -> `[`HttpHandler`](../-http-handler.md)`): `[`Filter`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../then.md) | `fun `[`Filter`](./index.md)`.then(next: `[`Filter`](./index.md)`): `[`Filter`](./index.md)<br>`fun `[`Filter`](./index.md)`.then(next: `[`HttpHandler`](../-http-handler.md)`): `[`HttpHandler`](../-http-handler.md)<br>`fun `[`Filter`](./index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [NoOp](../-no-op.md) | `val Filter.Companion.NoOp: `[`Filter`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthRequestTrackingFilter](../../org.http4k.security.oauth.server/-auth-request-tracking-filter/index.md) | `class AuthRequestTrackingFilter : `[`Filter`](./index.md) |
| [CatchLensFailure](../../org.http4k.filter/-server-filters/-catch-lens-failure.md) | `object CatchLensFailure : `[`Filter`](./index.md)<br>Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour. |
| [ChaosEngine](../../org.http4k.chaos/-chaos-engine/index.md) | `class ChaosEngine : `[`Filter`](./index.md)<br>The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine is deactivated, so activate() needs to be called to witness any change in behaviour, |
| [ClientValidationFilter](../../org.http4k.security.oauth.server/-client-validation-filter/index.md) | `class ClientValidationFilter : `[`Filter`](./index.md) |
| [GenerateDataClasses](../../org.http4k.filter/-generate-data-classes/index.md) | `class GenerateDataClasses<out NODE> : `[`Filter`](./index.md)<br>This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GenerateXmlDataClasses](../../org.http4k.filter/-generate-xml-data-classes/index.md) | `class GenerateXmlDataClasses<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Filter`](./index.md)<br>This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GZipContentTypes](../../org.http4k.filter/-response-filters/-g-zip-content-types/index.md) | `class GZipContentTypes : `[`Filter`](./index.md)<br>GZipping of the response where the content-type (sans-charset) matches an allowed list of compressible types. |
| [GZipContentTypes](../../org.http4k.filter/-server-filters/-g-zip-content-types/index.md) | `class GZipContentTypes : `[`Filter`](./index.md)<br>Basic GZip and Gunzip support of Request/Response where the content-type is in the allowed list. Only Gunzips requests which contain "transfer-encoding" header containing 'gzip' Only Gzips responses when request contains "accept-encoding" header containing 'gzip' and the content-type (sans-charset) is one of the compressible types. |
| [OAuthRedirectionFilter](../../org.http4k.security/-o-auth-redirection-filter/index.md) | `class OAuthRedirectionFilter : `[`Filter`](./index.md) |
