# Barn Hunt Helpers

[![trackgit-views](https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/lhaq315q9lwjmpm6k47l)](https://trackgit.com)

Here are some bits and pieces that are possibly useful when drawing
[Barn Hunt][] maps using [Inkscape][].

I (and Sandra) have, for several years, been using Inkscape, along
with some helper scripts and custom extensions, to draw our maps. The
sample course map on the official [BHA Judging Assignment Cheat
Sheet][cheat] is one of mine.

I've recently reworked these helpers to allow the use of recent versions
of Inkscape (I had been using version 0.9x).

Here is an attempt to make these bits more publicly available.

Currently, documentation is sparse to non-existent.  Hopefully, this
is useful, nonetheless.  Feedback is certainly appreciated.

## Getting Started

I use these helpers under Linux, but, in theory, they should work in
Windows, and maybe even on a Mac.

Installation outline:

1. First, install [Inkscape][].
   These helpers should work with any Inkscape with version 1.0 or later.
2. Install [python](https://python.org), version 3.7 or greater.
3. Install my [barnhunt](https://github.com/barnhunt/barnhunt#installation)
   script.
4. Finally run the `barnhunt install` sub-command to install
   my [inkscape plugins](https://github.com/barnhunt/inkex-bh)
   and [inkscape symbol sets](https://github.com/barnhunt/bh-symbols).

## Author

Jeff Dairiki, BHAJ-221A, <dairiki@dairiki.org>

[Inkscape]: https://inkscape.org/ (The Inkscape home page)
[Barn Hunt]: https://www.barnhunt.com/ (Barn Hunt — a fabulous sport for dogs)
[cheat]: https://www.barnhunt.com/judge/resources.php?download=147
(The official BHA "Judging Assignment Cheat Sheet" which includes,
as an example, one of my course maps, drawn using Inkscape.)
