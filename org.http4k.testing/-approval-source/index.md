[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ApprovalSource](./index.md)

# ApprovalSource

`interface ApprovalSource`

The backing store where the approved and actual content will be stored.

### Functions

| Name | Summary |
|---|---|
| [actualFor](actual-for.md) | `abstract fun actualFor(testName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ReadWriteResource`](../-read-write-resource/index.md) |
| [approvedFor](approved-for.md) | `abstract fun approvedFor(testName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ReadResource`](../-read-resource/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [FileSystemApprovalSource](../-file-system-approval-source/index.md) | `class FileSystemApprovalSource : `[`ApprovalSource`](./index.md) |
