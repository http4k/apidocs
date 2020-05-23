[http4k](../index.md) / [org.http4k.format](./index.md)

## Package org.http4k.format

Common code relevant to the various message format implementations (eg. JSON).

### Types

| Name | Summary |
|---|---|
| [Argo](-argo/index.md) | `object Argo : `[`Json`](-json/index.md)`<JsonNode>` |
| [AutoMappingConfiguration](-auto-mapping-configuration/index.md) | This is the generic interface used to configure auto-mapping functionality for message format libraries. The various methods here can be used to provide custom mapping behaviour (say for domain classes).`interface AutoMappingConfiguration<BUILDER>` |
| [AutoMarshalling](-auto-marshalling/index.md) | `abstract class AutoMarshalling` |
| [AutoMarshallingJson](-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson : `[`AutoMarshalling`](-auto-marshalling/index.md) |
| [AutoMarshallingXml](-auto-marshalling-xml/index.md) | `abstract class AutoMarshallingXml : `[`AutoMarshalling`](-auto-marshalling/index.md) |
| [ConfigurableGson](-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonElement>` |
| [ConfigurableJackson](-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](-json-lib-auto-marshalling-json/index.md)`<JsonNode>` |
| [ConfigurableJacksonXml](-configurable-jackson-xml/index.md) | `open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](-auto-marshalling-xml/index.md) |
| [ConfigurableKotlinxSerialization](-configurable-kotlinx-serialization/index.md) | `open class ConfigurableKotlinxSerialization : `[`Json`](-json/index.md)`<JsonElement>` |
| [ConfigurableMoshi](-configurable-moshi/index.md) | `open class ConfigurableMoshi : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md) |
| [Gson](-gson.md) | To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.`object Gson : `[`ConfigurableGson`](-configurable-gson/index.md) |
| [Jackson](-jackson.md) | To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.`object Jackson : `[`ConfigurableJackson`](-configurable-jackson/index.md) |
| [JacksonXml](-jackson-xml.md) | To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called.`object JacksonXml : `[`ConfigurableJacksonXml`](-configurable-jackson-xml/index.md) |
| [Json](-json/index.md) | This is the contract for all JSON implementations`interface Json<NODE>` |
| [JsonLibAutoMarshallingJson](-json-lib-auto-marshalling-json/index.md) | `abstract class JsonLibAutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](-auto-marshalling-json/index.md)`, `[`Json`](-json/index.md)`<NODE>` |
| [JsonType](-json-type/index.md) | `enum class JsonType` |
| [KotlinxSerialization](-kotlinx-serialization.md) | To implement custom JSON configuration, create your own object singleton extending ConfigurableKotlinxSerialization.`object KotlinxSerialization : `[`ConfigurableKotlinxSerialization`](-configurable-kotlinx-serialization/index.md) |
| [Moshi](-moshi.md) | To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.`object Moshi : `[`ConfigurableMoshi`](-configurable-moshi/index.md) |
| [Xml](-xml/index.md) | `object Xml : `[`AutoMarshallingXml`](-auto-marshalling-xml/index.md) |

### Exceptions

| Name | Summary |
|---|---|
| [InvalidJsonException](-invalid-json-exception/index.md) | `class InvalidJsonException : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.fasterxml.jackson.databind.ObjectMapper](com.fasterxml.jackson.databind.-object-mapper/index.md) |  |
| [com.fasterxml.jackson.module.kotlin.KotlinModule](com.fasterxml.jackson.module.kotlin.-kotlin-module/index.md) |  |
| [com.google.gson.Gson](com.google.gson.-gson/index.md) |  |
| [com.google.gson.GsonBuilder](com.google.gson.-gson-builder/index.md) |  |
| [com.squareup.moshi.Moshi.Builder](com.squareup.moshi.-moshi.-builder/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [bigDecimal](big-decimal.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.bigDecimal(inFn: (`[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`) -> OUT, outFn: (OUT) -> `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [bigInteger](big-integer.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.bigInteger(inFn: (`[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`) -> OUT, outFn: (OUT) -> `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [boolean](boolean.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.boolean(inFn: (`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`) -> OUT, outFn: (OUT) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [double](double.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.double(outFn: (OUT) -> `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, inFn: (`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`) -> OUT): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [duration](duration.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.duration(inFn: (`[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`) -> OUT, outFn: (OUT) -> `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [instant](instant.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.instant(inFn: (`[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`) -> OUT, outFn: (OUT) -> `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [int](int.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.int(inFn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> OUT, outFn: (OUT) -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [jsonHttpBodyLens](json-http-body-lens.md) | `fun jsonHttpBodyLens(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [localDate](local-date.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.localDate(inFn: (`[`LocalDate`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDate.html)`) -> OUT, outFn: (OUT) -> `[`LocalDate`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDate.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [localDateTime](local-date-time.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.localDateTime(inFn: (`[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`) -> OUT, outFn: (OUT) -> `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [localTime](local-time.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.localTime(inFn: (`[`LocalTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalTime.html)`) -> OUT, outFn: (OUT) -> `[`LocalTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalTime.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [long](long.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.long(inFn: (`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`) -> OUT, outFn: (OUT) -> `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [offsetDateTime](offset-date-time.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.offsetDateTime(inFn: (`[`OffsetDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetDateTime.html)`) -> OUT, outFn: (OUT) -> `[`OffsetDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetDateTime.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [offsetTime](offset-time.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.offsetTime(inFn: (`[`OffsetTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetTime.html)`) -> OUT, outFn: (OUT) -> `[`OffsetTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetTime.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [text](text.md) | This is the set of utility methods which avoid the noise of creating a BiDiMapping when specifying mappings.`fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(inFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> OUT, outFn: (OUT) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>`<br>Utility method for when only writing/serialization is required`fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(mapping: (OUT) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>`<br>Utility method for when only reading/deserialization is required`fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.text(mapping: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> OUT): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [uri](uri.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.uri(inFn: (`[`Uri`](../org.http4k.core/-uri/index.md)`) -> OUT, outFn: (OUT) -> `[`Uri`](../org.http4k.core/-uri/index.md)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [uuid](uuid.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.uuid(inFn: (`[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`) -> OUT, outFn: (OUT) -> `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [withStandardMappings](with-standard-mappings.md) | This is the set of (additional) standardised string &lt;-&gt; type mappings which http4k supports out of the box.`fun <T> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<T>.withStandardMappings(): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<T>` |
| [yearMonth](year-month.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.yearMonth(inFn: (`[`YearMonth`](https://docs.oracle.com/javase/9/docs/api/java/time/YearMonth.html)`) -> OUT, outFn: (OUT) -> `[`YearMonth`](https://docs.oracle.com/javase/9/docs/api/java/time/YearMonth.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
| [zonedDateTime](zoned-date-time.md) | `fun <BUILDER, OUT> `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>.zonedDateTime(inFn: (`[`ZonedDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/ZonedDateTime.html)`) -> OUT, outFn: (OUT) -> `[`ZonedDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/ZonedDateTime.html)`): `[`AutoMappingConfiguration`](-auto-mapping-configuration/index.md)`<BUILDER>` |
