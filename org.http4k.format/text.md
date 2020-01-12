[http4k](../index.md) / [org.http4k.format](index.md) / [text](./text.md)

# text

`inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(noinline inFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`OUT`](text.md#OUT)`, noinline outFn: (`[`OUT`](text.md#OUT)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L90)

This is the set of utility methods which avoid the noise of creating a BiDiMapping when specifying mappings.

`@JvmName("textSerialize") inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(noinline mapping: (`[`OUT`](text.md#OUT)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L148)

Utility method for when only writing/serialization is required

`@JvmName("textDeserialize") inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(noinline mapping: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`OUT`](text.md#OUT)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L154)

Utility method for when only reading/deserialization is required

