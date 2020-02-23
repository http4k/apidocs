[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](index.md) / [withBasePath](./with-base-path.md)

# withBasePath

`fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ContractRoutingHttpHandler`](index.md)

Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match()
To follow the trend of immutability, this will generally be a new instance.

