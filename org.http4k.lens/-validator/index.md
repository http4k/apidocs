[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Validator](./index.md)

# Validator

`enum class Validator`

Runs through a list of lenses and extracts the values from each one, collecting the errors

### Enum Values

| Name | Summary |
|---|---|
| [Strict](-strict.md) |  |
| [Feedback](-feedback.md) |  |
| [Ignore](-ignore.md) |  |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> invoke(entity: T, vararg lenses: `[`LensExtractor`](../-lens-extractor/index.md)`<T, *>): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`>` |
