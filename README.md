# Perl Dancer Book
A book about the Perl Dancer micro-framework.

## Building the Chapters:
```
./build/tools/build_chapters.pl
```
NB: This will replace all `L<XXX>` tokens by `sections/XXX.pod` or `examples/XXX.pl`

## Running the Examples:
```
./build/tools/run.pl examples/XXX.pl
```

## TODO
* Find a way to build a complete PDF with a table of contents and an index at the end of the book.
* Footnotes are not rendered nicely in HTML, if possible, find a way to render them as real footnotes, like in Wikipedia for instance.
