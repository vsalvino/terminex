Terminex
========

This is a version of [IBM Plex Mono](https://github.com/IBM/plex) made more
usable in terminals and code editors with three additions:

* Slightly darker weight (based on IBM Plex Mono Text).
* Uses slashed zero instead of dotted zero.
* Dash is slightly longer.
* Addition of box drawing characters [from Adobe](https://github.com/adobe-type-tools/box-drawing)
  for use in terminals.

Aside from these changes, there is no difference in the actual glyphs between
these fonts and the original version of IBM Plex Mono - they mainly just contain
metadata modification.

![](Sample.png)


Installation
------------

Install the TTF files in this repo, and reference in your application as
"Terminex"


Source
------

1. Clone https://github.com/adobe-type-tools/box-drawing and run it from the
   command line to generate UFO of box drawing characters.

2. Download latest IBM Plex TTF files from: https://github.com/IBM/plex
   * IBM Plex Mono Text
   * IBM Plex Mono Text Italic
   * IBM Plex Mono Bold
   * IBM Plex MOno Bold Italic

3. Open each source TTF file in [FontForge](https://fontforge.org/en-US/).

4. To apply box drawing characters:
   * Select Element > Merge font...
   * Select the UFO folder.

5. To swap dotted zero for slashed zero:
   * Select View > Go to...
   * Go to "zero.alt1". Copy/paste into "zero".

6. To swap hyphen with en-dash:
   * Select View > Go to...
   * Go to "endash". Copy/paste into "hyphen".

7. Rename meta info:
   * Select Element > Font info...
   * Adjust family, name, weights so that all belong to family "Terminex".
