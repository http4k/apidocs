[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [DetectBinaryBody](./index.md)

# DetectBinaryBody

`interface DetectBinaryBody`

OpenWhisk Base64 encodes Binary requests and responses when they are sent to
the deployed Function. This interface allows for custom implementations of that logic,
which might be required if your function supports more than one endpoint (with mixed
request/response types).

### Functions

| Name | Summary |
|---|---|
| [isBinary](is-binary.md) | `abstract fun isBinary(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`abstract fun isBinary(request: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [Binary](-binary.md) | `val Binary: `[`DetectBinaryBody`](./index.md) |
| [BinaryRequestOnly](-binary-request-only.md) | `val BinaryRequestOnly: `[`DetectBinaryBody`](./index.md) |
| [BinaryResponseOnly](-binary-response-only.md) | `val BinaryResponseOnly: `[`DetectBinaryBody`](./index.md) |
| [NonBinary](-non-binary.md) | `val NonBinary: `[`DetectBinaryBody`](./index.md) |
