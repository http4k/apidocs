[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigureJackson](./index.md)

# ConfigureJackson

`class ConfigureJackson : `[`ConfigureAutoMarshallingJson`](../-configure-auto-marshalling-json/index.md)`<ObjectMapper>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/Jackson.kt#L93)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigureJackson()` |

### Functions

| Name | Summary |
|---|---|
| [done](done.md) | `fun done(): ObjectMapper` |
| [text](text.md) | `fun <T> text(mapping: `[`BiDiMapping`](../../org.http4k.lens/-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](text.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Add a customised string &lt;-&gt; T mapping to this JSON instance. |

### Extension Functions

| Name | Summary |
|---|---|
| [withStandardMappings](../with-standard-mappings.md) | `fun <T> `[`ConfigureAutoMarshallingJson`](../-configure-auto-marshalling-json/index.md)`<`[`T`](../with-standard-mappings.md#T)`>.withStandardMappings(): `[`T`](../with-standard-mappings.md#T)<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
