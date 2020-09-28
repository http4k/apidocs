[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractRoutingHttpHandler](index.md) / [withFilter](./with-filter.md)

# withFilter

`fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`ContractRoutingHttpHandler`](index.md)

NOTE: By default, filters for Contracts are applied *before* the Security filter. Use withPostSecurityFilter()
to achieve population of filters after security.

