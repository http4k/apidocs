[http4k](../index.md) / [org.http4k.lens](index.md) / [LensInjectorExtractor](./-lens-injector-extractor.md)

# LensInjectorExtractor

`interface LensInjectorExtractor<IN, OUT> : `[`LensExtractor`](-lens-extractor/index.md)`<IN, OUT>, `[`LensInjector`](-lens-injector/index.md)`<OUT, IN>`

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](-lens-failure/index.md)`>>` |
