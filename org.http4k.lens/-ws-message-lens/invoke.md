[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLens](index.md) / [invoke](./invoke.md)

# invoke

`open operator fun invoke(target: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): FINAL`

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)