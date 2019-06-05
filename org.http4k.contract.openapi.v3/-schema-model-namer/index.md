[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [SchemaModelNamer](./index.md)

# SchemaModelNamer

`interface SchemaModelNamer : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/AutoJsonToJsonSchema.kt#L106)

### Companion Object Properties

| Name | Summary |
|---|---|
| [Full](-full.md) | `val Full: `[`SchemaModelNamer`](./index.md) |
| [Simple](-simple.md) | `val Simple: `[`SchemaModelNamer`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [renderToResponse](../../org.http4k.template/kotlin.-function1/render-to-response.md) | `fun `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`.renderToResponse(viewModel: `[`ViewModel`](../../org.http4k.template/-view-model/index.md)`, status: `[`Status`](../../org.http4k.core/-status/index.md)` = OK, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)` = TEXT_HTML): `[`Response`](../../org.http4k.core/-response/index.md)<br>Convenience method for generating a Response from a view model. |
| [then](../../org.http4k.template/kotlin.-function1/then.md) | `fun `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`.then(that: `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`): `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)<br>Compose a TemplateRenderer with another, so you can fall back. |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
