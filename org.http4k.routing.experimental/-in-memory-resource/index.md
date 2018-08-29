[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [InMemoryResource](./index.md)

# InMemoryResource

`class InMemoryResource : `[`Resource`](../-resource/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/routing/experimental/InMemoryResource.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InMemoryResource(content: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, lastModified: Instant? = null, etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`? = null)`<br>`InMemoryResource(content: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, lastModified: Instant? = null, etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [etag](etag.md) | `val etag: `[`ETag`](../../org.http4k.core.etag/-e-tag/index.md)`?` |
| [lastModified](last-modified.md) | `val lastModified: Instant?` |
| [length](length.md) | `val length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |

### Inherited Properties

| Name | Summary |
|---|---|
| [headers](../-resource/headers.md) | `open val headers: `[`Headers`](../../org.http4k.core/-headers.md) |

### Functions

| Name | Summary |
|---|---|
| [openStream](open-stream.md) | `fun openStream(): `[`ByteArrayInputStream`](http://docs.oracle.com/javase/6/docs/api/java/io/ByteArrayInputStream.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-resource/invoke.md) | `open fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`MemoryResponse`](../../org.http4k.core/-memory-response/index.md) |
| [isModifiedSince](../-resource/is-modified-since.md) | `open fun isModifiedSince(instant: Instant): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosControls](../../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |
