[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`WsMessageLensSpec`](index.md)`<NEXT>`

Create another WsMessageLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a WsMessage.

