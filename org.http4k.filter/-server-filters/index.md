[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ServerFilters](./index.md)

# ServerFilters

`object ServerFilters`

### Types

| Name | Summary |
|---|---|
| [ApiKeyAuth](-api-key-auth/index.md) | ApiKey token checking.`object ApiKeyAuth` |
| [BasicAuth](-basic-auth/index.md) | Simple Basic Auth credential checking.`object BasicAuth` |
| [BearerAuth](-bearer-auth/index.md) | Bearer Auth token checking.`object BearerAuth` |
| [CatchAll](-catch-all/index.md) | Last gasp filter which catches all exceptions and returns a formatted Internal Server Error.`object CatchAll` |
| [CatchLensFailure](-catch-lens-failure.md) | Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour.`object CatchLensFailure : `[`Filter`](../../org.http4k.core/-filter.md) |
| [CopyHeaders](-copy-headers/index.md) | Copy headers from the incoming request to the outbound response.`object CopyHeaders` |
| [Cors](-cors/index.md) | Add Cors headers to the Response, according to the passed CorsPolicy`object Cors` |
| [GZip](-g-zip/index.md) | Basic GZip and Gunzip support of Request/Response. Only Gunzips requests which contain "transfer-encoding" header containing 'gzip' Only Gzips responses when request contains "accept-encoding" header containing 'gzip'.`object GZip` |
| [GZipContentTypes](-g-zip-content-types/index.md) | Basic GZip and Gunzip support of Request/Response where the content-type is in the allowed list. Only Gunzips requests which contain "transfer-encoding" header containing 'gzip' Only Gzips responses when request contains "accept-encoding" header containing 'gzip' and the content-type (sans-charset) is one of the compressible types.`class GZipContentTypes : `[`Filter`](../../org.http4k.core/-filter.md) |
| [InitialiseRequestContext](-initialise-request-context/index.md) | Initialise a RequestContext for each request which passes through the Filter stack,`object InitialiseRequestContext` |
| [ReplaceResponseContentsWithStaticFile](-replace-response-contents-with-static-file/index.md) | Intercepts responses and replaces the contents with contents of the statically loaded resource. By default, this Filter replaces the contents of unsuccessful requests with the contents of a file named after the status code.`object ReplaceResponseContentsWithStaticFile` |
| [RequestTracing](-request-tracing/index.md) | Adds Zipkin request tracing headers to the incoming request and outbound response. (traceid, spanid, parentspanid)`object RequestTracing` |
| [SetContentType](-set-content-type/index.md) | Sets the Content Type response header on the Response.`object SetContentType` |

### Functions

| Name | Summary |
|---|---|
| [CatchLensFailure](-catch-lens-failure.md) | Converts Lens extraction failures into correct HTTP responses (Bad Requests/UnsupportedMediaType). This is required when using lenses to automatically unmarshall inbound requests. Note that LensFailures from unmarshalling upstream Response objects are NOT caught to avoid incorrect server behaviour.`fun CatchLensFailure(failResponseFn: (`[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = {
        Response(BAD_REQUEST.description(it.failures.joinToString("; ")))
    }): <ERROR CLASS>` |

### Extension Properties

| Name | Summary |
|---|---|
| [MicrometerMetrics](../-micrometer-metrics.md) | `val `[`ServerFilters`](./index.md)`.MicrometerMetrics: `[`MicrometerMetrics`](../-micrometer-metrics/index.md) |
| [OpenTelemetryMetrics](../-open-telemetry-metrics.md) | `val `[`ServerFilters`](./index.md)`.OpenTelemetryMetrics: `[`OpenTelemetryMetrics`](../-open-telemetry-metrics/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [HandleRemoteRequestFailed](../-handle-remote-request-failed.md) | Handle exceptions from remote calls and convert them into sensible server-side errors. Optionally pass in a function to format the response body from the exception.`fun `[`ServerFilters`](./index.md)`.HandleRemoteRequestFailed(exceptionToBody: `[`RemoteRequestFailed`](../../org.http4k.cloudnative/-remote-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Throwable::getLocalizedMessage): `[`Filter`](../../org.http4k.core/-filter.md) |
| [HandleUpstreamRequestFailed](../-handle-upstream-request-failed.md) | `fun `[`ServerFilters`](./index.md)`.~~HandleUpstreamRequestFailed~~(exceptionToBody: `[`RemoteRequestFailed`](../../org.http4k.cloudnative/-remote-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { localizedMessage }): `[`Filter`](../../org.http4k.core/-filter.md) |
| [OpenTelemetryTracing](../-open-telemetry-tracing.md) | `fun `[`ServerFilters`](./index.md)`.OpenTelemetryTracing(tracer: Tracer = Http4kOpenTelemetry.tracer, spanNamer: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it.uri.toString() }, error: (`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { _, t -> t.localizedMessage }): `[`Filter`](../../org.http4k.core/-filter.md) |
| [ProcessFiles](../-process-files.md) | Process files on upload using the passed consumer, which returns a reference. The form file is replaced in the form with this reference.`fun `[`ServerFilters`](./index.md)`.ProcessFiles(fileConsumer: (File) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): <ERROR CLASS>` |
