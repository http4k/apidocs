[http4k](../../index.md) / [org.http4k.contract](../index.md) / [JsonErrorResponseRenderer](./index.md)

# JsonErrorResponseRenderer

`class JsonErrorResponseRenderer<NODE> : `[`ErrorResponseRenderer`](../-error-response-renderer/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonErrorResponseRenderer(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>)` |

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `fun badRequest(lensFailure: `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |
