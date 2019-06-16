[http4k](../../index.md) / [org.http4k.testing](../index.md) / [FileSystemApprovalSource](./index.md)

# FileSystemApprovalSource

`class FileSystemApprovalSource : `[`ApprovalSource`](../-approval-source/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/approvalSource.kt#L23)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FileSystemApprovalSource(base: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [actualFor](actual-for.md) | `fun actualFor(testName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ReadWriteResource`](../-read-write-resource/index.md) |
| [approvedFor](approved-for.md) | `fun approvedFor(testName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ReadResource`](../-read-resource/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
