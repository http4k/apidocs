[http4k](../../index.md) / [org.http4k.events](../index.md) / [EventsFilter](./index.md)

# EventsFilter

`interface EventsFilter : (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/events/events.kt#L15)

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md)`): `[`EventsFilter`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [then](../then.md) | `fun `[`EventsFilter`](./index.md)`.then(next: `[`EventsFilter`](./index.md)`): `[`EventsFilter`](./index.md)<br>`fun `[`EventsFilter`](./index.md)`.then(next: `[`Events`](../-events.md)`): `[`Events`](../-events.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
