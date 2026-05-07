# Nano PDF

> Lightweight PDF text extraction and manipulation using Python and system tools.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/Marrowleaf/hermes-nano-pdf)

## Features

- Extract text content from PDF files
- Merge and split PDF documents
- Convert PDFs to plain text or Markdown
- Batch processing support for multiple PDFs
- Lightweight with minimal dependencies

## Installation

```bash
hermes skills install productivity/nano-pdf
```

Or manually clone into `~/.hermes/skills/productivity/nano-pdf/`.

## Usage

```
nano-pdf extract /path/to/document.pdf
nano-pdf extract /path/to/folder/ --batch
nano-pdf merge file1.pdf file2.pdf --output combined.pdf
nano-pdf split large.pdf --pages 1-10
```

## Configuration

No additional configuration required.

## Requirements

- Python 3.8+
- `pymupdf` (for PDF text extraction)
- Poppler Utils (for PDF manipulation)

## License

MIT

## Related Hermes Skills
- [hermes-airtable](https://github.com/Marrowleaf/hermes-airtable) — Airtable integration and automation
- [hermes-budget-tracker](https://github.com/Marrowleaf/hermes-budget-tracker) — Personal budget tracking and analysis
- [hermes-consensus-engine](https://github.com/Marrowleaf/hermes-consensus-engine) — Multi-model consensus and decision engine
- [hermes-notion](https://github.com/Marrowleaf/hermes-notion) — Notion integration and management
- [hermes-ocr-and-documents](https://github.com/Marrowleaf/hermes-ocr-and-documents) — OCR and document processing
