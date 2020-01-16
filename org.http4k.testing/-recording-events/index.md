[http4k](../../index.md) / [org.http4k.testing](../index.md) / [RecordingEvents](./index.md)

# RecordingEvents

`class RecordingEvents : `[`Events`](../../org.http4k.events/-events.md)`, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Event`](../../org.http4k.events/-event/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/testing/RecordingEvents.kt#L10)

Simple recording events that can be used in tests

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RecordingEvents()`<br>Simple recording events that can be used in tests |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(p1: `[`Event`](../../org.http4k.events/-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [iterator](iterator.md) | `fun iterator(): `[`MutableIterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)`<`[`Event`](../../org.http4k.events/-event/index.md)`!>` |

### Extension Functions

| Name | Summary |
|---|---|
| [then](../../org.http4k.events/kotlin.-function1/then.md) | `fun `[`Events`](../../org.http4k.events/-events.md)`.then(next: `[`Events`](../../org.http4k.events/-events.md)`): `[`Events`](../../org.http4k.events/-events.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
