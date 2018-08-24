[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [JsonNodeProducer](./index.md)

# JsonNodeProducer

`interface JsonNodeProducer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/ErrorMessage.kt#L27)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun <ROOT : `[`NODE`](invoke.md#NODE)`, NODE> invoke(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](invoke.md#ROOT)`, `[`NODE`](invoke.md#NODE)`>): `[`NODE`](invoke.md#NODE) |

### Inheritors

| Name | Summary |
|---|---|
| [ErrorMessage](../-error-message/index.md) | `open class ErrorMessage : `[`JsonNodeProducer`](./index.md) |
