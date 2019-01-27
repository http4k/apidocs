[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMappingConfiguration](./index.md)

# AutoMappingConfiguration

`interface AutoMappingConfiguration<T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L22)

This is the main interface which should be

### Functions

| Name | Summary |
|---|---|
| [boolean](boolean.md) | `abstract fun <OUT> boolean(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, `[`OUT`](boolean.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>`<br>Add a customised boolean &lt;-&gt; T mapping to this JSON instance. |
| [decimal](decimal.md) | `abstract fun <OUT> decimal(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`, `[`OUT`](decimal.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>`<br>Add a customised decimal &lt;-&gt; T mapping to this JSON instance. |
| [done](done.md) | `abstract fun done(): `[`T`](index.md#T)<br>Finalise the mapping configurations. |
| [number](number.md) | `abstract fun <OUT> number(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`, `[`OUT`](number.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>`<br>Add a customised number &lt;-&gt; T mapping to this JSON instance. |
| [text](text.md) | `abstract fun <OUT> text(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OUT`](text.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>`<br>Add a customised string &lt;-&gt; T mapping to this JSON instance. |

### Extension Functions

| Name | Summary |
|---|---|
| [withStandardMappings](../with-standard-mappings.md) | `fun <T> `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>.withStandardMappings(): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>`<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
