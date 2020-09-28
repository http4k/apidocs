[http4k](../../index.md) / [org.http4k.events](../index.md) / [EventFilter](./index.md)

# EventFilter

`interface EventFilter : (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md)

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(fn: (`[`Events`](../-events.md)`) -> `[`Events`](../-events.md)`): <ERROR CLASS>` |

### Extension Functions

| Name | Summary |
|---|---|
| [then](../then.md) | `fun `[`EventFilter`](./index.md)`.then(next: `[`EventFilter`](./index.md)`): `[`EventFilter`](./index.md)<br>`fun `[`EventFilter`](./index.md)`.then(next: `[`Events`](../-events.md)`): `[`Events`](../-events.md) |
