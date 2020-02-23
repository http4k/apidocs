[http4k](../index.md) / [org.http4k.filter](index.md) / [ProcessFiles](./-process-files.md)

# ProcessFiles

`fun `[`ServerFilters`](-server-filters/index.md)`.ProcessFiles(fileConsumer: (File) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../org.http4k.core/-filter/index.md)

Process files on upload using the passed consumer, which returns a reference.
The form file is replaced in the form with this reference.

