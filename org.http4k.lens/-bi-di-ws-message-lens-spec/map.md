[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiWsMessageLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (OUT) -> NEXT, nextOut: (NEXT) -> OUT): `[`BiDiWsMessageLensSpec`](index.md)`<NEXT>`

Create another BiDiWsMessageLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be
used to extract or insert the final type from/into a WsMessage.

