[http4k](../../index.md) / [org.apache.commons.fileupload.util](../index.md) / [ParameterParser](index.md) / [parse](./parse.md)

# parse

`open fun parse(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, separators: `[`CharArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-array/index.html)`!): `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!`

Extracts a map of name/value pairs from the given string. Names are expected to be unique. Multiple separators may be specified and the earliest found in the input string is used.

### Parameters

`str` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: the string that contains a sequence of name/value pairs

`separators` - [CharArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-array/index.html)!: the name/value pairs separators

**Return**
[MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!,&nbsp;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!&gt;!: a map of name/value pairs

`open fun parse(str: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, separator: `[`Char`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)`): `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!`

Extracts a map of name/value pairs from the given string. Names are expected to be unique.

### Parameters

`str` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: the string that contains a sequence of name/value pairs

`separator` - [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html): the name/value pairs separator

**Return**
[MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!,&nbsp;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!&gt;!: a map of name/value pairs

