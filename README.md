This is a fork of https://github.com/svend/cuetools which adds two things to cuetag.sh:
- Removes UTF-8 byte order mark (BOM). Some cue files have those marks and they prevent cuetag.sh to work properly.
- Adds --no-utf8-convert flag to metaflac command for Japanese characters to work

# cuetools [![Build Status](https://travis-ci.org/rinri-d/cuetools-jp.svg?branch=master)](https://travis-ci.org/rinri-d/cuetools-jp)

cue and toc file parsers and utilities

https://github.com/svend/cuetools

Copyright (C) 2004, 2005, 2006, 2007, 2013 Svend Sorensen

cuetools is a set of utilities for working with Cue Sheet (cue) and Table of
Contents (toc) files.

It includes:

- `cueconvert` convert between the cue and toc formats
- `cuebreakpoints` print the breakpoints from a cue or toc file
- `cueprint` print disc and track information for a cue or toc file

Directory layout:

- `doc/` documentation (including man pages)
- `src/` all source files
- `src/lib/` scanning, parsing, and printing library
- `src/tools/` cue and toc tools

