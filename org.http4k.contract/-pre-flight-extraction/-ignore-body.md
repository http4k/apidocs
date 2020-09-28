[http4k](../../index.md) / [org.http4k.contract](../index.md) / [PreFlightExtraction](index.md) / [IgnoreBody](./-ignore-body.md)

# IgnoreBody

`val IgnoreBody: <ERROR CLASS>`

Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct
LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times.

