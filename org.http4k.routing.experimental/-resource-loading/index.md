[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoading](./index.md)

# ResourceLoading

`interface ResourceLoading : `[`Router`](../../org.http4k.routing/-router/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/experimental/ResourceLoaders.kt#L41)

A little convenience thunk to simplify implementing [Router](../../org.http4k.routing/-router/index.md) for resource loaders.

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | `abstract fun match(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?``open fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request. |

### Inheritors

| Name | Summary |
|---|---|
| [ClasspathResourceLoader](../-classpath-resource-loader/index.md) | `data class ClasspathResourceLoader : `[`Router`](../../org.http4k.routing/-router/index.md)`, `[`ResourceLoading`](./index.md) |
| [DirectoryResourceLoader](../-directory-resource-loader/index.md) | `data class DirectoryResourceLoader : `[`Router`](../../org.http4k.routing/-router/index.md)`, `[`ResourceLoading`](./index.md) |
