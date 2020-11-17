[http4k](../index.md) / [org.http4k.routing](index.md) / [graphQL](./graph-q-l.md)

# graphQL

`fun graphQL(handler: `[`GraphQLHandler`](../org.http4k.graphql/-graph-q-l-handler.md)`, badRequestFn: (`[`LensFailure`](../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { Response(BAD_REQUEST) }): `[`RoutingHttpHandler`](-routing-http-handler/index.md)

Routing plugin for GraphQL handling.

`fun <T> graphQL(handler: `[`GraphQLWithContextHandler`](../org.http4k.graphql/-graph-q-l-with-context-handler.md)`<T>, getContext: (`[`Request`](../org.http4k.core/-request/index.md)`) -> T, badRequestFn: (`[`LensFailure`](../org.http4k.lens/-lens-failure/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { Response(BAD_REQUEST) }): `[`RoutingHttpHandler`](-routing-http-handler/index.md)

Routing plugin for GraphQL handling with contextual data.

