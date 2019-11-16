# FreeBASIC Collection

[FreeBASIC](https://www.freebasic.net/) is a multiplatform, free/open source BASIC compiler.
FreeBASIC provides a high level of syntax compatibility with programs originally written in QBasic.

This collection includes a select set of QBasic example programs modified to be compiled with FreeBASIC:

* [**Gorillas**](GORILLA.BAS) - an [artillery](https://en.wikipedia.org/wiki/Artillery_game) game
* [**Nibbles**](NIBBLES.BAS) - a classic [snake](https://en.wikipedia.org/wiki/Snake_(video_game_genre)) game

Release Notes:

* Sound is not currently supported.

  A temporary null `PLAY` statement library ([PlayNull.bi](PlayNull.bi) and [PlayNull.bas](PlayNull.bas)) is included.
  Other libraries exist, but are not without bugs.

* The collection can be compiled with:

      fbc -lib PlayNull.bas
      fbc NIBBLES.bas
      fbc -s gui GORILLA.bas
