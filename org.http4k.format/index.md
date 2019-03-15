[http4k](../index.md) / [org.http4k.format](./index.md)

## Package org.http4k.format

Common code relevant to the various message format implementations (eg. JSON).

### Types

| Name | Summary |
|---|---|
| [Argo](-argo/index.md) | `object Argo : `[`Json`](-json/index.md)`<JsonNode>` |
| [AutoMappingConfiguration](-auto-mapping-configuration/index.md) | `interface AutoMappingConfiguration<T>`<br>This is the generic interface used to configure auto-mapping functionality for message format libraries. The various methods here can be used to provide custom mapping behaviour (say for domain classes). |
| [AutoMarshallingJson](-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson` |
| [AutoMarshallingXml](-auto-marshalling-xml/index.md) | `abstract class AutoMarshallingXml` |
| [ConfigurableGson](-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonElement>` |
| [ConfigurableJackson](-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonNode>` |
| [ConfigurableJacksonXml](-configurable-jackson-xml/index.md) | `open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](-auto-marshalling-xml/index.md) |
| [ConfigurableMoshi](-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md) |
| [Gson](-gson.md) | `object Gson : `[`ConfigurableGson`](-configurable-gson/index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [Jackson](-jackson.md) | `object Jackson : `[`ConfigurableJackson`](-configurable-jackson/index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [JacksonXml](-jackson-xml.md) | `object JacksonXml : `[`ConfigurableJacksonXml`](-configurable-jackson-xml/index.md)<br>To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [Json](-json/index.md) | `interface Json<NODE>`<br>This is the contract for all JSON implementations |
| [JsonErrorResponseRenderer](-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<out NODE>` |
| [JsonLibAutoMarshallingJson](-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md)`, `[`Json`](-json/index.md)`<`[`NODE`](-json-lib-auto-marshalling-json/index.md#NODE)`>` |
| [JsonType](-json-type/index.md) | `enum class JsonType` |
| [Moshi](-moshi.md) | `object Moshi : `[`ConfigurableMoshi`](-configurable-moshi/index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [Xml](-xml/index.md) | `object Xml : `[`AutoMarshallingXml`](-auto-marshalling-xml/index.md) |

### Exceptions

| Name | Summary |
|---|---|
| [InvalidJsonException](-invalid-json-exception/index.md) | `class InvalidJsonException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.fasterxml.jackson.module.kotlin.KotlinModule](com.fasterxml.jackson.module.kotlin.-kotlin-module/index.md) |  |
| [com.google.gson.GsonBuilder](com.google.gson.-gson-builder/index.md) |  |
| [com.squareup.moshi.Moshi.Builder](com.squareup.moshi.-moshi.-builder/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [withStandardMappings](with-standard-mappings.md) | `fun <T> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`T`](with-standard-mappings.md#T)`>.withStandardMappings(): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`T`](with-standard-mappings.md#T)`>`<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
