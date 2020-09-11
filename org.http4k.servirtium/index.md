[http4k](../index.md) / [org.http4k.servirtium](./index.md)

## Package org.http4k.servirtium

### Types

| Name | Summary |
|---|---|
| [GitHub](-git-hub/index.md) | Read a file from a repository using the GitHub API.`class GitHub : `[`StorageProvider`](-storage-provider.md) |
| [GithubFile](-github-file/index.md) | `data class GithubFile` |
| [InteractionControl](-interaction-control/index.md) | Provides controls for interacting with an in-action Interaction recording.`interface InteractionControl` |
| [InteractionOptions](-interaction-options/index.md) | General controls for the Servirtium interactions and how they are recorded to the storage format. The manipulations are used to replace/remove any dynamic parts of the request (eg. "Date" header) so that the traffic can be correctly matched during the replay process.`interface InteractionOptions` |
| [InteractionStorage](-interaction-storage/index.md) | Provides storage for the recorded Servirtium interaction data.`interface InteractionStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>` |
| [ServirtiumServer](-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](-interaction-control/index.md) |
| [StorageProvider](-storage-provider.md) | `typealias StorageProvider = (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`InteractionStorage`](-interaction-storage/index.md) |
