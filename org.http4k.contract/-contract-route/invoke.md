[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoute](index.md) / [invoke](./invoke.md)

# invoke

`fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)

ContractRoutes are chiefly designed to operate within a contract {} block and not directly as an HttpHandler,
but this function exists to enable the testing of the ContractRoute logic outside of a wider contract context.
This means that certain behaviour is defaulted - chiefly the generation of NOT_FOUND and BAD_REQUEST responses.

