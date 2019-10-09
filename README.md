IBM Plex Mono Text
==================

This is a version of [IBM Plex Mono](https://github.com/IBM/plex) that has the
"Text" weight linked to the "Bold" weight. IBM Plex Mono (Regular) is a bit too
thin and grainy at small sizes on Windows with lower resolution screens; the
Text family/weight looks much more clear, especially on dark backgrounds.
However, since only the Regular version is linked to the Bold weight, when
using IBM Plex Mono Text there is technically no bold weight available and the
computer will try to artificially software-render the bold (which looks
terrible and also breaks the monospace nature of the font).

These fonts replace IBM Plex Mono Text/TextItalic, and add a copies of IBM Plex
Mono Bold/BoldItalic which are correctly linked.

This version of the font is ideal in terminals and code editors, where you
might want a slightly more readable version than IBM Plex Mono Regular, but
still want italics and bold to render properly.


Installation
------------

Install the TTF files in this repo. Note that this will overwrite the default
version of IBM Plex Mono Text/TextItalic if you have those installed (this is
the desired behavior - the font is identical except for metadata).


Usage
-----

Reference the font as "IBM Plex Mono Text". You can then use normal italic
or bold controls within your application, and they will pick up the correct
weights and styles.


Difference Between Upstream IBM Plex Mono
-----------------------------------------

There is no difference in the actual glyphs between these fonts and the official
version of IBM Plex Mono. The metadata of the TTF files have been altered to
properly link the text/italic/bold/bold-talic versions together under a single
family named "IBM Plex Mono Text".
