[http4k](../index.md) / [org.http4k.routing.experimental](./index.md)

## Package org.http4k.routing.experimental

### Types

| Name | Summary |
|---|---|
| [Resource](-resource/index.md) | `interface Resource : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ResourceLoaders](-resource-loaders/index.md) | `object ResourceLoaders` |
| [ResourceLoading](-resource-loading/index.md) | `interface ResourceLoading : `[`Router`](../org.http4k.routing/-router/index.md)<br>A little convenience thunk to simplify implementing [Router](../org.http4k.routing/-router/index.md) for resource loaders. |
| [ResourceSummary](-resource-summary/index.md) | `data class ResourceSummary` |
| [URLResource](-u-r-l-resource/index.md) | `data class URLResource : `[`Resource`](-resource/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [DirectoryRenderer](-directory-renderer.md) | `typealias DirectoryRenderer = (uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [simpleDirectoryRenderer](simple-directory-renderer.md) | `fun simpleDirectoryRenderer(uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [static](static.md) | `fun static(resourceLoader: `[`ResourceLoading`](-resource-loading/index.md)`): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
