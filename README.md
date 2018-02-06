Melo Melo Search
================
[![Travis Build Status](https://travis-ci.org/loveemu/melosearch.svg?branch=master)](https://travis-ci.org/loveemu/melosearch) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/gxwayd6df3jtqhgd/branch/master?svg=true)](https://ci.appveyor.com/project/loveemu/melosearch/branch/master)

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
