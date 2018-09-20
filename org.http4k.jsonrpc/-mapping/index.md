[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [Mapping](./index.md)

# Mapping

`class Mapping<IN, OUT> : `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/lenses.kt#L7)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Mapping(convert: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [meta](../../org.http4k.lens/-lens/meta.md) | `val meta: `[`Meta`](../../org.http4k.lens/-meta/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../../org.http4k.lens/-lens/invoke.md) | `open operator fun invoke(target: `[`IN`](../../org.http4k.lens/-lens/index.md#IN)`): `[`FINAL`](../../org.http4k.lens/-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
| [iterator](../../org.http4k.lens/-lens/iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../../org.http4k.lens/-meta/index.md)`>` |
| [toString](../../org.http4k.lens/-lens/to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
