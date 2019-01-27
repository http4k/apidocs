[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMappingConfiguration](./index.md)

# AutoMappingConfiguration

`interface AutoMappingConfiguration<T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L20)

This is the main interface which should be

### Functions

| Name | Summary |
|---|---|
| [done](done.md) | `abstract fun done(): `[`T`](index.md#T)<br>Finalise the mapping configurations. |
| [text](text.md) | `abstract fun <T> text(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](text.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a customised string &lt;-&gt; T mapping to this JSON instance. |

### Extension Functions

| Name | Summary |
|---|---|
| [withStandardMappings](../with-standard-mappings.md) | `fun <T> `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>.withStandardMappings(): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>`<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
