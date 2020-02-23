[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [SetBaseUriFrom](./index.md)

# SetBaseUriFrom

`object SetBaseUriFrom`

Sets the base uri (host + base path) on an outbound request. This is useful to separate configuration of remote endpoints
from the logic required to construct the rest of the request.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(uri: `[`Uri`](../../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
