[http4k](../index.md) / [org.http4k.servirtium](./index.md)

## Package org.http4k.servirtium

### Types

| Name | Summary |
|---|---|
| [ServirtiumContract](-servirtium-contract/index.md) | `interface ServirtiumContract`<br>Defines a test contract which can be used to implement recording or replaying of Servirtium-formatted tests |
| [ServirtiumReplayServer](-servirtium-replay-server/index.md) | `object ServirtiumReplayServer`<br>MiTM replay server which will match and replay recorded traffic read from the named Servirtium Markdown file. Incoming requests can be manipulated to ensure that it matches the expected request. |
| [ServirtumRecordingServer](-servirtum-recording-server/index.md) | `object ServirtumRecordingServer`<br>MiTM proxy server which sits inbetween the client and the target and stores traffic in the named Servirtium Markdown file. |
