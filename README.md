# oll-ji: Just Intonation notation for Lilypond

This package adds commands for notating music in just-intonation.

This repository is a fork of [openlilylib/ji](https://github.com/openlilylib/ji), a part of [openLilyLib](https://github.com/openlilylib).

## Installation

Install using [lyp](https://github.com/noteflakes/lyp)

```bash
lyp install oll-ji
```

## Usage

```lilypond
\require "oll-ji"

{
  \jiNote 1 7/4
}
```

Yes, documentation is lacking. For more information see the included [example](test/ji-test.ly)

