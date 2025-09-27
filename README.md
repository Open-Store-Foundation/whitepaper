# Open Store — Whitepaper

This repository contains the Open Store whitepaper in Markdown and generated PDFs in English and Russian.

## Contents

- `open-store-whitepaper-en.md`: English Markdown source
- `open-store-whitepaper-en.pdf`: English PDF (generated)
- `generate.sh`: Helper script to build PDFs with Pandoc + XeLaTeX
- `LICENSE`: MIT license for this repository

## Prerequisites

- Pandoc
- XeLaTeX (e.g., TeX Live or MacTeX)
- Fonts used by the docs: Georgia, Times New Roman

## Build

Run the helper script:

```bash
./generate.sh
```

Or run Pandoc directly:

```bash
pandoc open-store-whitepaper-en.md -o open-store-whitepaper-en.pdf --pdf-engine=xelatex
pandoc open-store-whitepaper-ru.md -o open-store-whitepaper-ru.pdf --pdf-engine=xelatex
```

## License

This repository is licensed under the MIT License. See `LICENSE` for details.
