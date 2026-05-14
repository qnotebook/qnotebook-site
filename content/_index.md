+++
title = "qnotebook"
template = "index.html"
+++

A **PyQt6 wiki editor** with true WYSIWYG editing over plain markdown files.
Heavily inspired by [Zim Desktop Wiki](https://zim-wiki.org), written
from the ground up — no code shared with Zim.

## What it does

Any directory with `.md` files is a notebook. qnotebook gives you a
single-surface WYSIWYG editor (one `QTextEdit`, no preview tab) that
round-trips cleanly to CommonMark + GFM on disk.

- Wikilinks: `[[Page]]`, `[[Foo:Bar]]`, `[[Target|alias]]`
- Headings, bold, italic, strike, inline & fenced code
- Ordered / unordered / nested lists, task lists with click-to-toggle
- Tables, blockquotes, horizontal rules
- Backlinks dock, back/forward navigation
- SQLite-backed backlink index in a `.qnotebook/` dotdir

## Install

```bash
git clone https://codeberg.org/qnotebook/qnotebook
cd qnotebook
just install-deps
just run /path/to/notebook
```

Source: [codeberg.org/qnotebook/qnotebook](https://codeberg.org/qnotebook/qnotebook)
