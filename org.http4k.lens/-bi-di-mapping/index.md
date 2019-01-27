[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](./index.md)

# BiDiMapping

`data class BiDiMapping<T>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L23)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiMapping(read: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`T`](index.md#T)`, write: (`[`T`](index.md#T)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it.toString() })` |

### Properties

| Name | Summary |
|---|---|
| [read](read.md) | `val read: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`T`](index.md#T) |
| [write](write.md) | `val write: (`[`T`](index.md#T)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [boolean](../boolean.md) | `fun BiDiMapping.Companion.boolean(): `[`BiDiMapping`](./index.md)`<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [double](../double.md) | `fun BiDiMapping.Companion.double(): `[`BiDiMapping`](./index.md)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [duration](../duration.md) | `fun BiDiMapping.Companion.duration(): `[`BiDiMapping`](./index.md)`<Duration>` |
| [float](../float.md) | `fun BiDiMapping.Companion.float(): `[`BiDiMapping`](./index.md)`<`[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [instant](../instant.md) | `fun BiDiMapping.Companion.instant(): `[`BiDiMapping`](./index.md)`<Instant>` |
| [int](../int.md) | `fun BiDiMapping.Companion.int(): `[`BiDiMapping`](./index.md)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](../local-date.md) | `fun BiDiMapping.Companion.localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiMapping`](./index.md)`<LocalDate>` |
| [localDateTime](../local-date-time.md) | `fun BiDiMapping.Companion.localDateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiMapping`](./index.md)`<LocalDateTime>` |
| [localTime](../local-time.md) | `fun BiDiMapping.Companion.localTime(formatter: DateTimeFormatter = ISO_LOCAL_TIME): `[`BiDiMapping`](./index.md)`<LocalTime>` |
| [long](../long.md) | `fun BiDiMapping.Companion.long(): `[`BiDiMapping`](./index.md)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](../non-empty-string.md) | `fun BiDiMapping.Companion.nonEmptyString(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [offsetDateTime](../offset-date-time.md) | `fun BiDiMapping.Companion.offsetDateTime(formatter: DateTimeFormatter = ISO_OFFSET_DATE_TIME): `[`BiDiMapping`](./index.md)`<OffsetDateTime>` |
| [offsetTime](../offset-time.md) | `fun BiDiMapping.Companion.offsetTime(formatter: DateTimeFormatter = ISO_OFFSET_TIME): `[`BiDiMapping`](./index.md)`<OffsetTime>` |
| [regex](../regex.md) | `fun BiDiMapping.Companion.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [uri](../uri.md) | `fun BiDiMapping.Companion.uri(): `[`BiDiMapping`](./index.md)`<`[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [url](../url.md) | `fun BiDiMapping.Companion.url(): `[`BiDiMapping`](./index.md)`<`[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`>` |
| [uuid](../uuid.md) | `fun BiDiMapping.Companion.uuid(): `[`BiDiMapping`](./index.md)`<`[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](../zoned-date-time.md) | `fun BiDiMapping.Companion.zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiMapping`](./index.md)`<ZonedDateTime>` |
