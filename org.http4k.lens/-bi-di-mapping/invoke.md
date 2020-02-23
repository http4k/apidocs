[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](index.md) / [invoke](./invoke.md)

# invoke

`@JvmName("asIn") operator fun invoke(out: OUT): IN`
`@JvmName("asOut") operator fun invoke(asIn: IN): OUT`
`operator inline fun <IN, reified T> invoke(noinline asOut: (IN) -> T, noinline asIn: (T) -> IN): `[`BiDiMapping`](index.md)`<IN, T>`