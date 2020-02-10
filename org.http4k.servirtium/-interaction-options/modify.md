[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionOptions](index.md) / [modify](./modify.md)

# modify

`open fun modify(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionOptions.kt#L21)

Modify received requests before they are stored. Use this to replace/remove dynamic parts of the message
before serialisation.

`open fun modify(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionOptions.kt#L27)

Modify received responses before they are stored. Use this to replace/remove dynamic parts of the message
before serialisation.

