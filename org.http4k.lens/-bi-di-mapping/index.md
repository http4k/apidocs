[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](./index.md)

# BiDiMapping

`class BiDiMapping<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L28)

A BiDiMapping defines a reusable bidirectional transformation between an input and output type

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiMapping(clazz: `[`Class`](http://docs.oracle.com/javase/6/docs/api/java/lang/Class.html)`<`[`OUT`](index.md#OUT)`>, asOut: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT)`, asIn: (`[`OUT`](index.md#OUT)`) -> `[`IN`](index.md#IN)`)`<br>A BiDiMapping defines a reusable bidirectional transformation between an input and output type |

### Properties

| Name | Summary |
|---|---|
| [asIn](as-in.md) | `val asIn: (`[`OUT`](index.md#OUT)`) -> `[`IN`](index.md#IN) |
| [asOut](as-out.md) | `val asOut: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT) |
| [clazz](clazz.md) | `val clazz: `[`Class`](http://docs.oracle.com/javase/6/docs/api/java/lang/Class.html)`<`[`OUT`](index.md#OUT)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: `[`OUT`](index.md#OUT)`): `[`IN`](index.md#IN)<br>`operator fun invoke(asIn: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT) |
| [map](map.md) | `fun <NEXT> map(nextOut: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextIn: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiMapping`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, T> invoke(asOut: (`[`IN`](invoke.md#IN)`) -> `[`T`](invoke.md#T)`, asIn: (`[`T`](invoke.md#T)`) -> `[`IN`](invoke.md#IN)`): `[`BiDiMapping`](./index.md)`<`[`IN`](invoke.md#IN)`, `[`T`](invoke.md#T)`>` |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [bigDecimal](../big-decimal.md) | `fun BiDiMapping.Companion.bigDecimal(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [bigInteger](../big-integer.md) | `fun BiDiMapping.Companion.bigInteger(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`>` |
| [boolean](../boolean.md) | `fun BiDiMapping.Companion.boolean(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [double](../double.md) | `fun BiDiMapping.Companion.double(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [duration](../duration.md) | `fun BiDiMapping.Companion.duration(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, Duration>` |
| [float](../float.md) | `fun BiDiMapping.Companion.float(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [instant](../instant.md) | `fun BiDiMapping.Companion.instant(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, Instant>` |
| [int](../int.md) | `fun BiDiMapping.Companion.int(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](../local-date.md) | `fun BiDiMapping.Companion.localDate(formatter: DateTimeFormatter = ISO_LOCAL_DATE): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalDate>` |
| [localDateTime](../local-date-time.md) | `fun BiDiMapping.Companion.localDateTime(formatter: DateTimeFormatter = ISO_LOCAL_DATE_TIME): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalDateTime>` |
| [localTime](../local-time.md) | `fun BiDiMapping.Companion.localTime(formatter: DateTimeFormatter = ISO_LOCAL_TIME): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, LocalTime>` |
| [long](../long.md) | `fun BiDiMapping.Companion.long(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](../non-empty-string.md) | `fun BiDiMapping.Companion.nonEmptyString(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [offsetDateTime](../offset-date-time.md) | `fun BiDiMapping.Companion.offsetDateTime(formatter: DateTimeFormatter = ISO_OFFSET_DATE_TIME): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OffsetDateTime>` |
| [offsetTime](../offset-time.md) | `fun BiDiMapping.Companion.offsetTime(formatter: DateTimeFormatter = ISO_OFFSET_TIME): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OffsetTime>` |
| [regex](../regex.md) | `fun BiDiMapping.Companion.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regexObject](../regex-object.md) | `fun BiDiMapping.Companion.regexObject(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>` |
| [uri](../uri.md) | `fun BiDiMapping.Companion.uri(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [url](../url.md) | `fun BiDiMapping.Companion.url(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`URL`](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)`>` |
| [uuid](../uuid.md) | `fun BiDiMapping.Companion.uuid(): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`UUID`](http://docs.oracle.com/javase/6/docs/api/java/util/UUID.html)`>` |
| [zonedDateTime](../zoned-date-time.md) | `fun BiDiMapping.Companion.zonedDateTime(formatter: DateTimeFormatter = ISO_ZONED_DATE_TIME): `[`BiDiMapping`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, ZonedDateTime>` |
