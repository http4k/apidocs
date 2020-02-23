[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](index.md) / [enable](./enable.md)

# enable

`fun enable(): `[`ChaosEngine`](index.md)

Turn on Chaos Engine using the pre-initialised chaotic behaviour. Note that this may not actually produce any
effect based on the configured behaviour (e.g. if there is a specific Trigger that is condition-based.)

`fun enable(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`ChaosEngine`](index.md)

Update with new simple Chaotic behaviour to be applied whenever the ChaosEngine is enabled.

`fun enable(stage: `[`Stage`](../-stage.md)`): `[`ChaosEngine`](index.md)

Update the new complex (multi-stage, triggers etc) Chaotic behaviour to be applied whenever the ChaosEngine is enabled.

