[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [GitHub](./index.md)

# GitHub

`class GitHub : `[`StorageProvider`](../-storage-provider.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/GitHub.kt#L25)

Read a file from a repository using the GitHub API.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GitHub(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, basePath: `[`Path`](https://docs.oracle.com/javase/9/docs/api/java/nio/file/Path.html)` = Paths.get(""), reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = SetBaseUriFrom(Uri.of("https://api.github.com")).then(JavaHttpClient()))`<br>Read a file from a repository using the GitHub API. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InteractionStorage`](../-interaction-storage/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
