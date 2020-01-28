[http4k](../index.md) / [org.http4k.servirtium](index.md) / [Github](./-github.md)

# Github

`fun InteractionStorage.Companion.Github(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, baseApiUri: `[`Uri`](../org.http4k.core/-uri/index.md)` = Uri.of("https://api.github.com"), http: `[`HttpHandler`](../org.http4k.core/-http-handler.md)` = SetBaseUriFrom(baseApiUri).then(JavaHttpClient())): `[`StorageProvider`](-storage-provider.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/storageProviders.kt#L23)

Read a file from a repository using the GitHub API.

