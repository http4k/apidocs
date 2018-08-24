[http4k](../index.md) / [org.http4k.routing.experimental](./index.md)

## Package org.http4k.routing.experimental

### Types

| Name | Summary |
|---|---|
| [ClasspathResourceLoader](-classpath-resource-loader/index.md) | `data class ClasspathResourceLoader : `[`Router`](../org.http4k.routing/-router/index.md)`, `[`ResourceLoading`](-resource-loading/index.md) |
| [DirectoryResourceLoader](-directory-resource-loader/index.md) | `data class DirectoryResourceLoader : `[`Router`](../org.http4k.routing/-router/index.md)`, `[`ResourceLoading`](-resource-loading/index.md) |
| [FileResource](-file-resource/index.md) | `class FileResource : `[`Resource`](-resource/index.md) |
| [InMemoryResource](-in-memory-resource/index.md) | `class InMemoryResource : `[`Resource`](-resource/index.md) |
| [Resource](-resource/index.md) | `interface Resource : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ResourceListingHandler](-resource-listing-handler/index.md) | `class ResourceListingHandler : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [ResourceLoaders](-resource-loaders/index.md) | `object ResourceLoaders` |
| [ResourceLoading](-resource-loading/index.md) | `interface ResourceLoading : `[`Router`](../org.http4k.routing/-router/index.md)<br>A little convenience thunk to simplify implementing [Router](../org.http4k.routing/-router/index.md) for resource loaders. |
| [ResourceSummary](-resource-summary/index.md) | `data class ResourceSummary` |
| [URLResource](-u-r-l-resource/index.md) | `data class URLResource : `[`Resource`](-resource/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [DirectoryRenderer](-directory-renderer.md) | `typealias DirectoryRenderer = (uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.String](kotlin.-string/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [simpleDirectoryRenderer](simple-directory-renderer.md) | `fun simpleDirectoryRenderer(uri: `[`Uri`](../org.http4k.core/-uri/index.md)`, dir: `[`ResourceSummary`](-resource-summary/index.md)`, resources: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ResourceSummary`](-resource-summary/index.md)`>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [static](static.md) | `fun static(resourceLoader: `[`Router`](../org.http4k.routing/-router/index.md)`): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) |
