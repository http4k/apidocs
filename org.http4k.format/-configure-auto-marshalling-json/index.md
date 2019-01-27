[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigureAutoMarshallingJson](./index.md)

# ConfigureAutoMarshallingJson

`interface ConfigureAutoMarshallingJson<T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/ConfigureAutoMarshallingJson.kt#L20)

This is the main interface which should be

### Functions

| Name | Summary |
|---|---|
| [done](done.md) | `abstract fun done(): `[`T`](index.md#T) |
| [text](text.md) | `abstract fun <T> text(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](text.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a customised string &lt;-&gt; T mapping to this JSON instance. |

### Extension Functions

| Name | Summary |
|---|---|
| [withStandardMappings](../with-standard-mappings.md) | `fun <T> `[`ConfigureAutoMarshallingJson`](./index.md)`<`[`T`](../with-standard-mappings.md#T)`>.withStandardMappings(): `[`T`](../with-standard-mappings.md#T)<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigureGsonBuilder](../-configure-gson-builder/index.md) | `class ConfigureGsonBuilder : `[`ConfigureAutoMarshallingJson`](./index.md)`<GsonBuilder>` |
| [ConfigureJackson](../-configure-jackson/index.md) | `class ConfigureJackson : `[`ConfigureAutoMarshallingJson`](./index.md)`<ObjectMapper>` |
| [ConfigureMoshi](../-configure-moshi/index.md) | `class ConfigureMoshi : `[`ConfigureAutoMarshallingJson`](./index.md)`<Builder>` |
