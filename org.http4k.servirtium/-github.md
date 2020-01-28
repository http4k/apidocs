[http4k](../index.md) / [org.http4k.servirtium](index.md) / [Github](./-github.md)

# Github

`fun InteractionStorage.Companion.Github(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, basePath: `[`Path`](https://docs.oracle.com/javase/9/docs/api/java/nio/file/Path.html)` = Path.of(""), reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, http: `[`HttpHandler`](../org.http4k.core/-http-handler.md)` = SetBaseUriFrom(Uri.of("https://api.github.com")).then(JavaHttpClient())): `[`StorageProvider`](-storage-provider.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/storageProviders.kt#L24)

Read a file from a repository using the GitHub API.

