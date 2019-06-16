[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ReadWriteResource](./index.md)

# ReadWriteResource

`interface ReadWriteResource : `[`ReadResource`](../-read-resource/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/approvalSource.kt#L11)

### Functions

| Name | Summary |
|---|---|
| [output](output.md) | `abstract fun output(): `[`OutputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [input](../-read-resource/input.md) | `abstract fun input(): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
