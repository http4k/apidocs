[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoaders](./index.md)

# ResourceLoaders

`object ResourceLoaders`

### Types

| Name | Summary |
|---|---|
| [Classpath](-classpath/index.md) | `object Classpath` |

### Functions

| Name | Summary |
|---|---|
| [Directory](-directory.md) | `fun Directory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes()): `[`Router`](../../org.http4k.routing/-router/index.md) |
| [ListingDirectory](-listing-directory.md) | `fun ListingDirectory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeTypes: `[`MimeTypes`](../../org.http4k.core/-mime-types/index.md)` = MimeTypes(), directoryRenderer: `[`DirectoryRenderer`](../-directory-renderer.md)` = ::simpleDirectoryRenderer): `[`Router`](../../org.http4k.routing/-router/index.md) |
