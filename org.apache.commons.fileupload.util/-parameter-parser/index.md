[http4k](../../index.md) / [org.apache.commons.fileupload.util](../index.md) / [ParameterParser](./index.md)

# ParameterParser

`open class ParameterParser`

A simple parser intended to parse sequences of name/value pairs.

 Parameter values are expected to be enclosed in quotes if they contain unsafe characters, such as '=' characters or separators. Parameter values are optional and can be omitted.



 `param1 = value; param2 = "anything goes; really"; param3`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A simple parser intended to parse sequences of name/value pairs. `ParameterParser()` |

### Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | Extracts a map of name/value pairs from the given string. Names are expected to be unique. Multiple separators may be specified and the earliest found in the input string is used.`open fun parse(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, separators: `[`CharArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-array/index.html)`!): `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!`<br>Extracts a map of name/value pairs from the given string. Names are expected to be unique.`open fun parse(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, separator: `[`Char`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)`): `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [setLowerCaseNames](set-lower-case-names.md) | Sets the flag if parameter names are to be converted to lower case when name/value pairs are parsed.`open fun setLowerCaseNames(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
