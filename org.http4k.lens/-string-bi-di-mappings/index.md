[http4k](../../index.md) / [org.http4k.lens](../index.md) / [StringBiDiMappings](./index.md)

# StringBiDiMappings

`object StringBiDiMappings` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L53)

A set of standardised String &lt;-&gt; Type conversions which are used throughout http4k

### Functions

| Name | Summary |
|---|---|
| [base64](base64.md) | `fun base64(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [bigDecimal](big-decimal.md) | `fun bigDecimal(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`>` |
| [bigInteger](big-integer.md) | `fun bigInteger(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`>` |
| [boolean](boolean.md) | `fun boolean(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [double](double.md) | `fun double(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [duration](duration.md) | `fun duration(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`!>` |
| [eventCategory](event-category.md) | `fun eventCategory(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`EventCategory`](../../org.http4k.events/-event-category/index.md)`>` |
| [float](float.md) | `fun float(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [instant](instant.md) | `fun instant(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`!>` |
| [int](int.md) | `fun int(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](local-date.md) | `fun localDate(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_DATE): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`LocalDate`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDate.html)`!>` |
| [localDateTime](local-date-time.md) | `fun localDateTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`!>` |
| [localTime](local-time.md) | `fun localTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`LocalTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalTime.html)`!>` |
| [long](long.md) | `fun long(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmpty](non-empty.md) | `fun nonEmpty(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [offsetDateTime](offset-date-time.md) | `fun offsetDateTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_OFFSET_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`OffsetDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetDateTime.html)`!>` |
| [offsetTime](offset-time.md) | `fun offsetTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_OFFSET_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`OffsetTime`](https://docs.oracle.com/javase/9/docs/api/java/time/OffsetTime.html)`!>` |
| [regex](regex.md) | `fun regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regexObject](regex-object.md) | `fun regexObject(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>` |
| [samplingDecision](sampling-decision.md) | `fun samplingDecision(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`SamplingDecision`](../../org.http4k.filter/-sampling-decision/index.md)`>` |
| [traceId](trace-id.md) | `fun traceId(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`TraceId`](../../org.http4k.filter/-trace-id/index.md)`>` |
| [uri](uri.md) | `fun uri(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [url](url.md) | `fun url(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html)`>` |
| [uuid](uuid.md) | `fun uuid(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`!>` |
| [zonedDateTime](zoned-date-time.md) | `fun zonedDateTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_ZONED_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`ZonedDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/ZonedDateTime.html)`!>` |

### Extension Functions

| Name | Summary |
|---|---|
| [authority](../authority.md) | `fun `[`StringBiDiMappings`](./index.md)`.authority(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Authority`](../../org.http4k.cloudnative.env/-authority/index.md)`>` |
| [host](../host.md) | `fun `[`StringBiDiMappings`](./index.md)`.host(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Host`](../../org.http4k.cloudnative.env/-host/index.md)`>` |
| [port](../port.md) | `fun `[`StringBiDiMappings`](./index.md)`.port(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`>` |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
