[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [OpenApi3](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`OpenApi3(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>, apiRenderer: `[`ApiRenderer`](../../org.http4k.contract.openapi/-api-renderer/index.md)`<`[`Api`](../-api/index.md)`<`[`NODE`](index.md#NODE)`>, `[`NODE`](index.md#NODE)`> = OpenApi3ApiRenderer(json), securityRenderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md)` = OpenApi3SecurityRenderer, errorResponseRenderer: `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)` = JsonErrorResponseRenderer(json))`

Contract renderer for OpenApi3 format JSON. By default, for the JSON schema generation, auto-naming of
object models is used as the input relies on JSON objects and not JVM classees.

