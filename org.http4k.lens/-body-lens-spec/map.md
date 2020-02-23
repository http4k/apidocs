[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLensSpec](index.md) / [map](./map.md)

# map

`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`BodyLensSpec`](index.md)`<NEXT>`

Create another BodyLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be
used to extract the final type from a Body.

