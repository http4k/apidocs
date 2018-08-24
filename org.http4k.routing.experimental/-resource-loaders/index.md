[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoaders](./index.md)

# ResourceLoaders

`object ResourceLoaders` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/experimental/ResourceLoaders.kt#L10)

### Functions

| Name | Summary |
|---|---|
| [Classpath](-classpath.md) | `fun Classpath(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/", mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes(), constantLastModified: Instant? = Instant.now().truncatedTo(ChronoUnit.SECONDS), lastModifiedFinder: (path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> Instant? = { constantLastModified }): `[`ClasspathResourceLoader`](../-classpath-resource-loader/index.md) |
| [Directory](-directory.md) | `fun Directory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes()): `[`DirectoryResourceLoader`](../-directory-resource-loader/index.md) |
| [ListingDirectory](-listing-directory.md) | `fun ListingDirectory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes(), directoryRenderer: `[`DirectoryRenderer`](../-directory-renderer.md)` = ::simpleDirectoryRenderer): `[`DirectoryResourceLoader`](../-directory-resource-loader/index.md) |
