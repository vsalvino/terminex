IBM Plex Terminal
=================

This is a version of [IBM Plex Mono](https://github.com/IBM/plex) made more
usable in terminals and code editors, where you might want a slightly darker /
more readable version than IBM Plex Mono Regular, and need the box drawing
characters, but still want italics and bold to render properly.


Why "Text" weight instead of "Regular"
--------------------------------------

IBM Plex Mono (Regular) is a bit too thin and grainy at small sizes on Windows
with lower resolution screens; the Text family/weight looks much more clear,
especially on dark backgrounds. However, since only the Regular version is
linked to the Bold weight, when using IBM Plex Mono Text there is technically no
bold weight available and the computer will try to artificially software-render
the bold (which looks terrible and also breaks the monospace nature of the
font).


Installation
------------

Install the TTF files in this repo.


Usage
-----

Reference the font as "IBM Plex Terminal". You can then use normal italic
or bold controls within your application, and they will pick up the correct
weights and styles.


Difference Between Upstream IBM Plex Mono
-----------------------------------------

There is no difference in the actual glyphs between these fonts and the official
version of IBM Plex Mono. Box Drawing Characters were added from the
[generic glyphs provided by Source Code Pro](https://github.com/adobe-type-tools/box-drawing).
The metadata of the TTF files have been altered to properly link the
text/italic/bold/bold-talic versions together under a single family named
"IBM Plex Terminal".
