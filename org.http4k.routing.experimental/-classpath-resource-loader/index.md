[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ClasspathResourceLoader](./index.md)

# ClasspathResourceLoader

`data class ClasspathResourceLoader : `[`Router`](../../org.http4k.routing/-router/index.md)`, `[`ResourceLoading`](../-resource-loading/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/experimental/ClasspathResourceLoader.kt#L9)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClasspathResourceLoader(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes(), lastModifiedFinder: (path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> Instant?)` |

### Properties

| Name | Summary |
|---|---|
| [basePackagePath](base-package-path.md) | `val basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [lastModifiedFinder](last-modified-finder.md) | `val lastModifiedFinder: (path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> Instant?` |
| [mimeTypes](mime-types.md) | `val mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md) |

### Functions

| Name | Summary |
|---|---|
| [match](match.md) | `fun match(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Resource`](../-resource/index.md)`?` |

### Inherited Functions

| Name | Summary |
|---|---|
| [match](../../org.http4k.routing/-router/match.md) | `abstract fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?`<br>Attempt to supply an HttpHandler which can service the passed request. |
