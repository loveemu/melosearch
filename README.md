Melo Melo Search
================

Small utility to search a byte sequence by specified melody.

Note: The search engine uses only the key of notes. Others, such as lengths, will be ignored.

Usage
-----

Syntax: `MeloSearch (options) [input file] "[MML]"`

Note: `<` increases octave, and `>` decreases octave.

### Options

--help
  : show this help

-q
  : quiet mode, prints only errors and offsets

-l[length]
  : max distance between notes (in bytes) (default: `-l6`)

-eq
  : assume that notes must be equally spaced (-l means exact interval)
