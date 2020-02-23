[http4k](../../index.md) / [org.http4k.lens](../index.md) / [ContentNegotiation](./index.md)

# ContentNegotiation

`interface ContentNegotiation`

Modes for determining if a passed content type is acceptable.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(expected: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, actual: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [None](-none.md) | No validation is done on the received content type at all`val None: `[`ContentNegotiation`](./index.md) |
| [NonStrict](-non-strict.md) | If present, the received Content-type header passed back MUST equal the expected Content-type, including directive`val NonStrict: `[`ContentNegotiation`](./index.md) |
| [Strict](-strict.md) | The received Content-type header passed back MUST equal the expected Content-type, including directive`val Strict: `[`ContentNegotiation`](./index.md) |
| [StrictNoDirective](-strict-no-directive.md) | The received Content-type header passed back MUST equal the expected Content-type, not including the directive`val StrictNoDirective: `[`ContentNegotiation`](./index.md) |
