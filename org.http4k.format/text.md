[http4k](../index.md) / [org.http4k.format](index.md) / [text](./text.md)

# text

`inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(noinline inFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> OUT, noinline outFn: (OUT) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>`

This is the set of utility methods which avoid the noise of creating a BiDiMapping when specifying mappings.

`@JvmName("textSerialize") inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(noinline mapping: (OUT) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>`

Utility method for when only writing/serialization is required

`@JvmName("textDeserialize") inline fun <BUILDER, reified OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(noinline mapping: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> OUT): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>`

Utility method for when only reading/deserialization is required

