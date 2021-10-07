Terminex
========

This is a version of [IBM Plex Mono](https://github.com/IBM/plex) made more
usable in terminals and code editors with a few additions:

* Slightly darker weight (based on IBM Plex Mono Text).
* Uses slashed zero instead of dotted zero.
* Dash is slightly longer.
* ~~Addition of box drawing characters [from Adobe](https://github.com/adobe-type-tools/box-drawing)
  for use in terminals.~~ As of version 6, IBM Plex Mono now provides box
  drawing characters!

Aside from these changes, there is no difference in the actual glyphs between
these fonts and the original version of IBM Plex Mono - they mainly just contain
metadata modification.


Installation
------------

Install the TTF files in this repo, and reference in your application as
"Terminex"


Source
------

1. Download latest IBM Plex TTF files from: https://github.com/IBM/plex
   * IBM Plex Mono Text
   * IBM Plex Mono Text Italic
   * IBM Plex Mono Bold
   * IBM Plex Mono Bold Italic

2. Open each source TTF file in [FontForge](https://fontforge.org/en-US/).

3. To swap dotted zero for slashed zero:
   * Select View > Go to...
   * Go to "zero.alt01". Copy/paste into "zero".

4. To swap hyphen with en-dash:
   * Select View > Go to...
   * Go to "endash". Copy/paste into "hyphen".

5. Rename meta info:
   * Select Element > Font info...
   * Adjust family, name, weights so that all belong to family "Terminex".
