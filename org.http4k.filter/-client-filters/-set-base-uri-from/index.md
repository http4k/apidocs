[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [SetBaseUriFrom](./index.md)

# SetBaseUriFrom

`object SetBaseUriFrom` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L64)

Sets the base uri (host + base path) on an outbound request. This is useful to separate configuration of remote endpoints
from the logic required to construct the rest of the request.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(uri: `[`Uri`](../../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
