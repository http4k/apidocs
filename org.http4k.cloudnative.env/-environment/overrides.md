[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Environment](index.md) / [overrides](./overrides.md)

# overrides

`open infix fun overrides(that: `[`Environment`](index.md)`): `[`Environment`](index.md)

Overlays the configuration set in this Environment on top of the values in the passed Environment.
Used to chain: eg. Local File -&gt; System Properties -&gt; Env Properties -&gt; Defaults

