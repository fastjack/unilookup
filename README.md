# unilookup

A simple CLI Python 3 utility for looking up unicode codepoints.

This utility is now available on PyPI and can be simply installed via `pipx install unilookup`.

Simply run `unilookup` and send the data you wish to look up through stdin, and it'll spit out a nice ASCII table. Since version 0.2 it also supports passing the string as a command line parameter.

Example invocation of `unilookup`:
![Example invocation](docs/unilookup-example.png)

Originally based on https://github.com/miestasmia/unilookup. Ported to Python 3 there wasn't much left of the origin code thanks to Python 3's built-in unicodedata library.
