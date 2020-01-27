[http4k](../index.md) / [org.http4k.servirtium](./index.md)

## Package org.http4k.servirtium

### Types

| Name | Summary |
|---|---|
| [InteractionControl](-interaction-control/index.md) | `interface InteractionControl` |
| [InteractionOptions](-interaction-options/index.md) | `interface InteractionOptions` |
| [InteractionStorage](-interaction-storage.md) | `interface InteractionStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>` |
| [InteractionStorageLookup](-interaction-storage-lookup/index.md) | `interface InteractionStorageLookup : (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`InteractionStorage`](-interaction-storage.md)<br>Provides a way of providing a storage layer for |
| [ServirtiumServer](-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](-interaction-control/index.md) |
