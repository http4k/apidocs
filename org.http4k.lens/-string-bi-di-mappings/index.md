[http4k](../../index.md) / [org.http4k.lens](../index.md) / [StringBiDiMappings](./index.md)

# StringBiDiMappings

`object StringBiDiMappings` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L47)

A set of standardised String &lt;-&gt; Type conversions which are used throughout http4k

### Functions

| Name | Summary |
|---|---|
| [bigDecimal](big-decimal.md) | `fun bigDecimal(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [bigInteger](big-integer.md) | `fun bigInteger(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`>` |
| [boolean](boolean.md) | `fun boolean(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [double](double.md) | `fun double(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [duration](duration.md) | `fun duration(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, Duration>` |
| [float](float.md) | `fun float(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [instant](instant.md) | `fun instant(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, Instant>` |
| [int](int.md) | `fun int(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](local-date.md) | `fun localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalDate>` |
| [localDateTime](local-date-time.md) | `fun localDateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalDateTime>` |
| [localTime](local-time.md) | `fun localTime(formatter: DateTimeFormatter = ISO_LOCAL_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalTime>` |
| [long](long.md) | `fun long(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmpty](non-empty.md) | `fun nonEmpty(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [offsetDateTime](offset-date-time.md) | `fun offsetDateTime(formatter: DateTimeFormatter = ISO_OFFSET_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OffsetDateTime>` |
| [offsetTime](offset-time.md) | `fun offsetTime(formatter: DateTimeFormatter = ISO_OFFSET_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OffsetTime>` |
| [regex](regex.md) | `fun regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regexObject](regex-object.md) | `fun regexObject(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>` |
| [uri](uri.md) | `fun uri(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [url](url.md) | `fun url(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`>` |
| [uuid](uuid.md) | `fun uuid(): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](zoned-date-time.md) | `fun zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiMapping`](../-bi-di-mapping/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, ZonedDateTime>` |
