[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [GitHub](./index.md)

# GitHub

`class GitHub : `[`StorageProvider`](../-storage-provider.md)

Read a file from a repository using the GitHub API.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Read a file from a repository using the GitHub API.`GitHub(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, basePath: `[`Path`](https://docs.oracle.com/javase/9/docs/api/java/nio/file/Path.html)` = Paths.get(""), reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = SetHostFrom(Uri.of("https://api.github.com")).then(JavaHttpClient()))` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InteractionStorage`](../-interaction-storage/index.md) |
