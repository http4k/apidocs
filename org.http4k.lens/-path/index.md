[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Path](./index.md)

# Path

`object Path : `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`

### Functions

| Name | Summary |
|---|---|
| [fixed](fixed.md) | `fun fixed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`PathLens`](../-path-lens/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [base64](../base64.md) | `fun `[`Path`](./index.md)`.base64(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [bigDecimal](../big-decimal.md) | `fun `[`Path`](./index.md)`.bigDecimal(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`>` |
| [bigInteger](../big-integer.md) | `fun `[`Path`](./index.md)`.bigInteger(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`>` |
| [boolean](../boolean.md) | `fun `[`Path`](./index.md)`.boolean(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [dateTime](../date-time.md) | `fun `[`Path`](./index.md)`.dateTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_DATE_TIME): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`!>` |
| [double](../double.md) | `fun `[`Path`](./index.md)`.double(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [duration](../duration.md) | `fun `[`Path`](./index.md)`.duration(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`!>` |
| [float](../float.md) | `fun `[`Path`](./index.md)`.float(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [instant](../instant.md) | `fun `[`Path`](./index.md)`.instant(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Instant`](https://docs.oracle.com/javase/9/docs/api/java/time/Instant.html)`!>` |
| [int](../int.md) | `fun `[`Path`](./index.md)`.int(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [localDate](../local-date.md) | `fun `[`Path`](./index.md)`.localDate(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_DATE): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`LocalDate`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDate.html)`!>` |
| [localTime](../local-time.md) | `fun `[`Path`](./index.md)`.localTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_LOCAL_TIME): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`LocalTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalTime.html)`!>` |
| [long](../long.md) | `fun `[`Path`](./index.md)`.long(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [nonEmptyString](../non-empty-string.md) | `fun `[`Path`](./index.md)`.nonEmptyString(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regex](../regex.md) | `fun `[`Path`](./index.md)`.regex(pattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, group: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [regexObject](../regex-object.md) | `fun `[`Path`](./index.md)`.regexObject(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>` |
| [string](../string.md) | `fun `[`Path`](./index.md)`.string(): `[`Path`](./index.md) |
| [uri](../uri.md) | `fun `[`Path`](./index.md)`.uri(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [uuid](../uuid.md) | `fun `[`Path`](./index.md)`.uuid(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`!>` |
| [yearMonth](../year-month.md) | `fun `[`Path`](./index.md)`.yearMonth(): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`YearMonth`](https://docs.oracle.com/javase/9/docs/api/java/time/YearMonth.html)`!>` |
| [zonedDateTime](../zoned-date-time.md) | `fun `[`Path`](./index.md)`.zonedDateTime(formatter: `[`DateTimeFormatter`](https://docs.oracle.com/javase/9/docs/api/java/time/format/DateTimeFormatter.html)` = ISO_ZONED_DATE_TIME): `[`BiDiPathLensSpec`](../-bi-di-path-lens-spec/index.md)`<`[`ZonedDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/ZonedDateTime.html)`!>` |
