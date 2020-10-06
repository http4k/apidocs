[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](index.md) / [SetHostFrom](./-set-host-from.md)

# SetHostFrom

`fun SetHostFrom(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../org.http4k.core/-filter.md)

Sets the host on an outbound request. This is useful to separate configuration of remote endpoints
from the logic required to construct the rest of the request.

