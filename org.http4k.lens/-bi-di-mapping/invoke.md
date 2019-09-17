[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](index.md) / [invoke](./invoke.md)

# invoke

`@JvmName("asIn") operator fun invoke(out: `[`OUT`](index.md#OUT)`): `[`IN`](index.md#IN) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L40)
`@JvmName("asOut") operator fun invoke(asIn: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L43)
`inline operator fun <IN, reified T> invoke(noinline asOut: (`[`IN`](invoke.md#IN)`) -> `[`T`](invoke.md#T)`, noinline asIn: (`[`T`](invoke.md#T)`) -> `[`IN`](invoke.md#IN)`): `[`BiDiMapping`](index.md)`<`[`IN`](invoke.md#IN)`, `[`T`](invoke.md#T)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L46)