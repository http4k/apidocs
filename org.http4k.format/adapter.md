[http4k](../index.md) / [org.http4k.format](index.md) / [adapter](./adapter.md)

# adapter

`inline fun <reified T : JsonAdapter<K>, reified K> adapter(noinline fn: (Moshi) -> T): `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, (Moshi) -> T>`

Convenience function to create Moshi Adapter.

