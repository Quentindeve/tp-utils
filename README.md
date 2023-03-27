# tp-utils

My personal scripts for creating TP (Travaux Pratiques / Practical Works) Markdown files.

# tp-render

Renders your markdown file into PDF, and opens it

# tp-create

Creates a Markdown file according to the template /etc/tp-create/markdown.md

# About ``disable_float.tex``

This file exists to disable image floating in PDF rendering because Pandoc tends to do weird things with images. I don't know if it's because of Pandoc or the PDF engine but here we go.

# Dependencies

Pandoc, sh

# Install

```sh
chmod +x ./install.sh

sudo ./install.sh
```
