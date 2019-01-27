[http4k](../index.md) / [org.http4k.format](./index.md)

## Package org.http4k.format

Common code relevant to the various message format implementations (eg. JSON).

### Types

| Name | Summary |
|---|---|
| [Argo](-argo/index.md) | `object Argo : `[`Json`](-json/index.md)`<JsonNode>` |
| [AutoMarshallingJson](-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson` |
| [ConfigurableGson](-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonElement>` |
| [ConfigurableJackson](-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonNode>` |
| [ConfigurableMoshi](-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md) |
| [ConfigureAutoMarshallingJson](-configure-auto-marshalling-json/index.md) | `interface ConfigureAutoMarshallingJson<T>`<br>This is the main interface which should be |
| [ConfigureGsonBuilder](-configure-gson-builder/index.md) | `class ConfigureGsonBuilder : `[`ConfigureAutoMarshallingJson`](-configure-auto-marshalling-json/index.md)`<GsonBuilder>` |
| [ConfigureJackson](-configure-jackson/index.md) | `class ConfigureJackson : `[`ConfigureAutoMarshallingJson`](-configure-auto-marshalling-json/index.md)`<ObjectMapper>` |
| [ConfigureMoshi](-configure-moshi/index.md) | `class ConfigureMoshi : `[`ConfigureAutoMarshallingJson`](-configure-auto-marshalling-json/index.md)`<Builder>` |
| [Gson](-gson.md) | `object Gson : `[`ConfigurableGson`](-configurable-gson/index.md) |
| [Jackson](-jackson.md) | `object Jackson : `[`ConfigurableJackson`](-configurable-jackson/index.md) |
| [Json](-json/index.md) | `interface Json<NODE>`<br>This is the contract for all JSON implementations |
| [JsonErrorResponseRenderer](-json-error-response-renderer/index.md) | `class JsonErrorResponseRenderer<out NODE>` |
| [JsonLibAutoMarshallingJson](-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md)`, `[`Json`](-json/index.md)`<`[`NODE`](-json-lib-auto-marshalling-json/index.md#NODE)`>` |
| [JsonType](-json-type/index.md) | `enum class JsonType` |
| [Moshi](-moshi.md) | `object Moshi : `[`ConfigurableMoshi`](-configurable-moshi/index.md) |
| [Xml](-xml/index.md) | `object Xml` |

### Exceptions

| Name | Summary |
|---|---|
| [InvalidJsonException](-invalid-json-exception/index.md) | `class InvalidJsonException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |

### Functions

| Name | Summary |
|---|---|
| [withStandardMappings](with-standard-mappings.md) | `fun <T> `[`ConfigureAutoMarshallingJson`](-configure-auto-marshalling-json/index.md)`<`[`T`](with-standard-mappings.md#T)`>.withStandardMappings(): `[`T`](with-standard-mappings.md#T)<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
