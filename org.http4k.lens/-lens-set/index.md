[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSet](./index.md)

# LensSet

`class LensSet<IN, in OUT>`

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): (`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>, IN) -> IN` |
| [map](map.md) | `fun <NEXT> map(nextFn: (NEXT) -> OUT): `[`LensSet`](./index.md)`<IN, NEXT>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, OUT> invoke(setFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>, IN) -> IN): `[`LensSet`](./index.md)`<IN, OUT>` |
