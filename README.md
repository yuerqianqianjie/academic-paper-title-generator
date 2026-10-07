# Academic Paper Title Generator

A Codex skill for generating, refining, and evaluating professional English titles for academic papers.

## What it does

This skill helps turn a manuscript, abstract, outline, keyword list, or research notes into clear and discoverable English title options. It emphasizes:

- Accurate representation of the paper's contribution
- Searchable field-specific keywords
- Concise, readable phrasing
- Appropriate title structures for different disciplines
- Explicit checks against overclaiming and ambiguous wording

## Supported inputs

You can provide:

- Manuscripts in PDF, Word, LaTeX, Markdown, or plain text
- Abstracts, outlines, keywords, or research notes
- Figure and table captions
- Methods, findings, and contribution summaries

For long manuscripts, the skill prioritizes the title page, abstract, introduction, conclusion, keywords, headings, captions, and stated contributions.

## Use with Codex

Install or copy this directory into your Codex skills directory, then invoke it with:

`Use $academic-paper-title-generator to generate English academic paper title options from my manuscript or research notes.`

The skill normally returns:

1. A brief summary of the inferred paper focus
2. Eight to twelve title options grouped by style
3. Two or three recommended titles with tradeoffs
4. Optional shorter, more formal, journal-style, or keyword-optimized revisions

## Repository structure

```text
.
├── SKILL.md                 # Skill instructions
├── LICENSE                  # MIT license
└── agents/
    └── openai.yaml          # Codex display metadata and default prompt
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
