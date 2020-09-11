[http4k](../index.md) / [org.http4k.routing.experimental](./index.md)

## Package org.http4k.routing.experimental

### Types

| Name | Summary |
|---|---|
| [DirectoryRenderer](-directory-renderer.md) | `typealias DirectoryRenderer = (uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [Foo](-foo/index.md) | `class Foo` |
| [InMemoryResource](-in-memory-resource/index.md) | `class InMemoryResource : `[`Resource`](-resource/index.md) |
| [Resource](-resource/index.md) | `interface Resource : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ResourceListingHandler](-resource-listing-handler/index.md) | `class ResourceListingHandler : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ResourceLoaders](-resource-loaders/index.md) | `object ResourceLoaders` |
| [ResourceLoading](-resource-loading/index.md) | A little convenience thunk to simplify implementing [Router](../org.http4k.routing/-router/index.md) for resource loaders.`interface ResourceLoading : `[`Router`](../org.http4k.routing/-router/index.md) |
| [ResourceSummary](-resource-summary/index.md) | `data class ResourceSummary` |
| [URLResource](-u-r-l-resource/index.md) | `data class URLResource : `[`Resource`](-resource/index.md) |

### Functions

| Name | Summary |
|---|---|
| [simpleDirectoryRenderer](simple-directory-renderer.md) | `fun simpleDirectoryRenderer(uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [static](static.md) | `fun static(resourceLoader: `[`Router`](../org.http4k.routing/-router/index.md)`): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
