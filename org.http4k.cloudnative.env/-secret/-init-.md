[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Secret](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`Secret(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)``Secret(input: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)`

A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array.
You can "use" the value only once, after which the value is destroyed

