[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMappingConfiguration](./index.md)

# AutoMappingConfiguration

`interface AutoMappingConfiguration<T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L12)

This is the generic interface used to configure auto-mapping functionality for message format libraries.
The various methods here can be used to provide custom mapping behaviour (say for domain classes).

### Functions

| Name | Summary |
|---|---|
| [bigDecimal](big-decimal.md) | `abstract fun <OUT> bigDecimal(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`, `[`OUT`](big-decimal.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [bigInteger](big-integer.md) | `abstract fun <OUT> bigInteger(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`, `[`OUT`](big-integer.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [boolean](boolean.md) | `abstract fun <OUT> boolean(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, `[`OUT`](boolean.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [done](done.md) | `abstract fun done(): `[`T`](index.md#T)<br>Finalise the mapping configurations. |
| [double](double.md) | `abstract fun <OUT> double(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, `[`OUT`](double.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [int](int.md) | `abstract fun <OUT> int(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, `[`OUT`](int.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [long](long.md) | `abstract fun <OUT> long(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, `[`OUT`](long.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |
| [text](text.md) | `abstract fun <OUT> text(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`OUT`](text.md#OUT)`>): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](index.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [withStandardMappings](../with-standard-mappings.md) | `fun <T> `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>.withStandardMappings(): `[`AutoMappingConfiguration`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>`<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
