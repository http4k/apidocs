[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](index.md) / [withFilter](./with-filter.md)

# withFilter

`abstract fun withFilter(new: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`RoutingHttpHandler`](index.md)

Returns a RoutingHttpHandler which applies the passed Filter to all received requests before servicing them.
To follow the trend of immutability, this will generally be a new instance.

