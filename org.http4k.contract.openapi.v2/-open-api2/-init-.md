[http4k](../../index.md) / [org.http4k.contract.openapi.v2](../index.md) / [OpenApi2](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`OpenApi2(apiInfo: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>, baseUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null, extensions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OpenApiExtension`](../../org.http4k.contract.openapi/-open-api-extension/index.md)`> = emptyList(), securityRenderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md)` = OpenApi2SecurityRenderer, schemaGenerator: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`> = JsonToJsonSchema(json), errorResponseRenderer: `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md)` = JsonErrorResponseRenderer(json))`

Contract renderer for OpenApi2 format JSON. Note that for the JSON schema generation, auto-naming of
object models is used as the input relies on JSON objects and not JVM classees.

