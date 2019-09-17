[http4k](../../index.md) / [org.http4k.events](../index.md) / [EventFilter](./index.md)

# EventFilter

`interface EventFilter : (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/events/events.kt#L21)

An EventFilter is used to create pipelines for Event processing.

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md)`): `[`EventFilter`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [then](../then.md) | `fun `[`EventFilter`](./index.md)`.then(next: `[`EventFilter`](./index.md)`): `[`EventFilter`](./index.md)<br>`fun `[`EventFilter`](./index.md)`.then(next: `[`Events`](../-events.md)`): `[`Events`](../-events.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
