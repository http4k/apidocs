[http4k](../index.md) / [org.http4k.format](./index.md)

## Package org.http4k.format

Common code relevant to the various message format implementations (eg. JSON).

### Types

| Name | Summary |
|---|---|
| [Argo](-argo/index.md) | `object Argo : `[`Json`](-json/index.md)`<`[`JsonNode`](http://argo.sourceforge.net/javadoc/argo/jdom/JsonNode.html)`>` |
| [AutoMappingConfiguration](-auto-mapping-configuration/index.md) | `interface AutoMappingConfiguration<BUILDER>`<br>This is the generic interface used to configure auto-mapping functionality for message format libraries. The various methods here can be used to provide custom mapping behaviour (say for domain classes). |
| [AutoMarshallingJson](-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson` |
| [AutoMarshallingXml](-auto-marshalling-xml/index.md) | `abstract class AutoMarshallingXml` |
| [ConfigurableGson](-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonElement>` |
| [ConfigurableJackson](-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<`[`JsonNode`](https://fasterxml.github.io/jackson-databind/javadoc/2.10/com/fasterxml/jackson/databind/JsonNode.html)`>` |
| [ConfigurableJacksonXml](-configurable-jackson-xml/index.md) | `open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](-auto-marshalling-xml/index.md) |
| [ConfigurableMoshi](-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md) |
| [Gson](-gson.md) | `object Gson : `[`ConfigurableGson`](-configurable-gson/index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [Jackson](-jackson.md) | `object Jackson : `[`ConfigurableJackson`](-configurable-jackson/index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [JacksonXml](-jackson-xml.md) | `object JacksonXml : `[`ConfigurableJacksonXml`](-configurable-jackson-xml/index.md)<br>To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called. |
| [Json](-json/index.md) | `interface Json<NODE>`<br>This is the contract for all JSON implementations |
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
| [com.fasterxml.jackson.databind.ObjectMapper](com.fasterxml.jackson.databind.-object-mapper/index.md) |  |
| [com.fasterxml.jackson.module.kotlin.KotlinModule](com.fasterxml.jackson.module.kotlin.-kotlin-module/index.md) |  |
| [com.google.gson.GsonBuilder](com.google.gson.-gson-builder/index.md) |  |
| [com.squareup.moshi.Moshi.Builder](com.squareup.moshi.-moshi.-builder/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [bigDecimal](big-decimal.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](big-decimal.md#BUILDER)`>.bigDecimal(inMapping: (`[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`) -> `[`OUT`](big-decimal.md#OUT)`, outMapping: (`[`OUT`](big-decimal.md#OUT)`) -> `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](big-decimal.md#BUILDER)`>` |
| [bigInteger](big-integer.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](big-integer.md#BUILDER)`>.bigInteger(inMapping: (`[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`) -> `[`OUT`](big-integer.md#OUT)`, outMapping: (`[`OUT`](big-integer.md#OUT)`) -> `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](big-integer.md#BUILDER)`>` |
| [boolean](boolean.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](boolean.md#BUILDER)`>.boolean(inMapping: (`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`) -> `[`OUT`](boolean.md#OUT)`, outMapping: (`[`OUT`](boolean.md#OUT)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](boolean.md#BUILDER)`>` |
| [double](double.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](double.md#BUILDER)`>.double(outMapping: (`[`OUT`](double.md#OUT)`) -> `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, inMapping: (`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`) -> `[`OUT`](double.md#OUT)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](double.md#BUILDER)`>` |
| [int](int.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](int.md#BUILDER)`>.int(inMapping: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`OUT`](int.md#OUT)`, outMapping: (`[`OUT`](int.md#OUT)`) -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](int.md#BUILDER)`>` |
| [jsonHttpBodyLens](json-http-body-lens.md) | `fun jsonHttpBodyLens(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [long](long.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](long.md#BUILDER)`>.long(inMapping: (`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`) -> `[`OUT`](long.md#OUT)`, outMapping: (`[`OUT`](long.md#OUT)`) -> `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](long.md#BUILDER)`>` |
| [text](text.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(inMapping: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`OUT`](text.md#OUT)`, outMapping: (`[`OUT`](text.md#OUT)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>`<br>This is the set of utility methods which avoid the creation of a BiDiMapping.`fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(mapping: (`[`OUT`](text.md#OUT)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>`<br>Utility method for when only writing/serialization is required`fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>.text(mapping: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`OUT`](text.md#OUT)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`BUILDER`](text.md#BUILDER)`>`<br>Utility method for when only reading/deserialization is required |
| [withStandardMappings](with-standard-mappings.md) | `fun <T> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`T`](with-standard-mappings.md#T)`>.withStandardMappings(): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<`[`T`](with-standard-mappings.md#T)`>`<br>This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box. |
