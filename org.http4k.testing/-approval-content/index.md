[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ApprovalContent](./index.md)

# ApprovalContent

`interface ApprovalContent`

Determines which parts of the HttpMessage will be compared.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(input: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)<br>`abstract operator fun invoke(input: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [EntireHttpMessage](-entire-http-message.md) | `fun EntireHttpMessage(): `[`ApprovalContent`](./index.md) |
| [HttpBodyOnly](-http-body-only.md) | `fun HttpBodyOnly(formatter: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it }): `[`ApprovalContent`](./index.md) |
