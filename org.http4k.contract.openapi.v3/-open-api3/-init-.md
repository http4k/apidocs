[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [OpenApi3](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`OpenApi3(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`<NODE>, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList())``OpenApi3(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList(), apiRenderer: `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](../-api/index.md)`<NODE>, NODE> = OpenApi3ApiRenderer(json), securityRenderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md)` = OpenApi3SecurityRenderer, errorResponseRenderer: `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)` = JsonErrorResponseRenderer(json))`

Contract renderer for OpenApi3 format JSON. For the JSON schema generation, naming of
object models will default to either reflective or hashcode based depending on if a Auto Json
is passed.

