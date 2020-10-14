[http4k](../../index.md) / [org.http4k.routing](../index.md) / [ParameterMatch](./index.md)

# ParameterMatch

`sealed class ParameterMatch : (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

### Functions

| Name | Summary |
|---|---|
| [and](and.md) | `infix fun and(that: `[`ParameterMatch`](./index.md)`): `[`ParameterMatch`](./index.md) |
| [bind](bind.md) | `infix fun bind(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`RoutingHttpHandler`](../-routing-http-handler/index.md)<br>`infix fun bind(handler: `[`RoutingHttpHandler`](../-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../-routing-http-handler/index.md) |
