[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensGet](./index.md)

# LensGet

`class LensGet<in IN, out OUT>`

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): (IN) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>` |
| [map](map.md) | `fun <NEXT> map(nextFn: (OUT) -> NEXT): `[`LensGet`](./index.md)`<IN, NEXT>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, OUT> invoke(getFn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, IN) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>): `[`LensGet`](./index.md)`<IN, OUT>` |
