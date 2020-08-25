[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionOptions](index.md) / [Defaults](./-defaults.md)

# Defaults

`val Defaults: `[`InteractionOptions`](index.md)

By default, no modifications are made to the raw traffic before it gets output to disk. This will
not be used very often as dynamic headers such as "Date" and "User-Agent" will almost always be present and
need to be stripped out.

