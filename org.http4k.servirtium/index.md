[http4k](../index.md) / [org.http4k.servirtium](./index.md)

## Package org.http4k.servirtium

### Types

| Name | Summary |
|---|---|
| [GithubFile](-github-file/index.md) | `data class GithubFile` |
| [InteractionControl](-interaction-control/index.md) | `interface InteractionControl`<br>Provides controls for interacting with an in-action Interaction recording. |
| [InteractionOptions](-interaction-options/index.md) | `interface InteractionOptions`<br>This controls how the Servirtium interactions are recorded to the storage format. The manipulations are used to replace/remove any dynamic parts of the request (eg. Date headers) so that the traffic can be correctly matched during the replay process. |
| [InteractionStorage](-interaction-storage/index.md) | `interface InteractionStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>`<br>Provides storage for the recorded Servirtium interaction data. |
| [ServirtiumServer](-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](-interaction-control/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [StorageProvider](-storage-provider.md) | `typealias StorageProvider = (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`InteractionStorage`](-interaction-storage/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Github](-github.md) | `fun InteractionStorage.Companion.Github(owner: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, repo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../org.http4k.core/-credentials/index.md)`, basePath: `[`Path`](https://docs.oracle.com/javase/9/docs/api/java/nio/file/Path.html)` = Path.of(""), reference: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, http: `[`HttpHandler`](../org.http4k.core/-http-handler.md)` = SetBaseUriFrom(Uri.of("https://api.github.com")).then(JavaHttpClient())): `[`StorageProvider`](-storage-provider.md)<br>Read a file from a repository using the GitHub API. |
