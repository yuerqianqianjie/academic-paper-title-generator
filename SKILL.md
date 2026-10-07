---
name: academic-paper-title-generator
description: Generate, refine, and evaluate professional English titles for academic papers from manuscript files or research notes. Use when the user asks for paper title ideas, title polishing, title comparison, journal-style academic titles, or English title generation from PDF, Word, LaTeX, Markdown, plain text, abstracts, outlines, keywords, methods, findings, or draft manuscripts.
---

# Academic Paper Title Generator

Use this skill to produce clear, discoverable, field-appropriate English titles for scholarly papers. Prioritize accuracy over cleverness: every title must be supported by the manuscript or notes provided by the user.

## Inputs

Accept manuscript content in many forms, including:

- PDF files (`.pdf`)
- Word documents (`.doc`, `.docx`)
- LaTeX sources (`.tex`, `.bib`, project folders, or pasted LaTeX)
- Markdown or plain text drafts (`.md`, `.txt`)
- Abstracts, outlines, keywords, figures/tables captions, or bullet-point research notes

When a file is provided, inspect or extract enough content to identify the field, topic, methods, data/materials, main findings, contribution, and target audience. For long manuscripts, focus first on the title page, abstract, introduction, conclusion, keywords, headings, figure captions, and stated contributions. If extraction is incomplete, state the limitation and generate titles from the available evidence.

## Workflow

1. Identify the research field, central problem, object of study, methods, main findings, and contribution.
2. Infer the title strategy that best fits the paper: descriptive, result-oriented, method-oriented, question-based, or compound.
3. Generate a diverse set of title options, normally 8-12 titles.
4. Include a concise rationale for the strongest options, especially when choosing between single and compound titles.
5. Recommend 2-3 best titles and explain the tradeoff between clarity, specificity, novelty, and searchability.
6. If the user requests revision, iterate toward the target journal style, word limit, tone, or keyword requirements.

## Core Principles

A strong academic paper title should:

- State the topic and scope clearly and concisely.
- Include essential searchable keywords.
- Accurately reflect the paper's actual contribution.
- Be as short as possible while preserving meaning, preferably under 20 words unless field norms require otherwise.
- Avoid filler such as "study," "investigation," "inquiry," "analysis," "evaluation," and "assessment" unless the wording is necessary.
- Avoid trendy claims such as "new" or "novel" unless the manuscript specifically supports that claim.
- Use abbreviations only when they are standard and recognizable in the field.
- Avoid ambiguous noun strings and unclear modifier relationships.
- Match the conventions of the target journal, conference, or discipline when known.

## Title Structures

Use one or more of these structures as appropriate:

- **Single title**: A direct phrase or sentence that states the research focus.
  Example: "Convergent selection of a WD40 protein that enhances grain yield in maize and rice"
- **Compound title**: A main title plus subtitle separated by a colon, dash, or question mark. Use the subtitle to add method, system, field, or result details.
  Example: "Hunting the eagle killer: A cyanobacterial neurotoxin causes vacuolar myelinopathy"
- **Result-oriented title**: Emphasize the main finding when it is robust and central.
  Example: "CARD8 is an inflammasome sensor for HIV-1 protease activity"
- **Method-oriented title**: Emphasize the technique when the methodological contribution is primary.
  Example: "Microbial single-cell RNA sequencing by split-pool barcoding"
- **Scope-oriented title**: Emphasize setting, population, dataset, corpus, material, or context when scope is a major differentiator.

## Common Patterns

Prefer patterns that make relationships explicit:

- Topic + field
- Topic + method
- Topic + result
- Topic + method + result
- Intervention/exposure + outcome + population/context
- Method/model + task + dataset/domain
- Mechanism + system/material/organism

## Discipline Guidance

Adjust length and style by field:

- Mathematics, physics, and computer science often prefer shorter titles.
- Chemistry, engineering, medicine, and interdisciplinary fields often tolerate longer titles when they clarify materials, methods, population, or outcomes.
- Clinical titles should usually include population, intervention/exposure, outcome, and study design when relevant.
- Humanities and social sciences may use compound titles more often, but the subtitle should still provide searchable specificity.

## Pitfalls

Avoid these problems:

- Ambiguous noun strings.
  Bad: "Cultural heritage audiovisual material multilingual search gathering requirements"
  Better: "Gathering requirements for multilingual searches of audiovisual materials in cultural heritage"
- Empty framing.
  Bad: "A study of the factors affecting..."
  Better: "Factors affecting..."
- Unsupported overclaiming.
  Bad: "A novel universal framework for..."
  Better: Use "framework" only if the paper demonstrates generality.
- Vague contribution words.
  Avoid relying on "approach," "perspective," "insights," or "exploration" unless the title also names the specific subject and contribution.

## Output Format

Unless the user asks for another format, respond with:

1. A brief summary of the inferred paper focus.
2. 8-12 title options grouped by style, such as descriptive, result-oriented, method-oriented, concise, or compound.
3. A short note on the best 2-3 options.
4. Optional refinements: shorter version, more formal version, journal-style version, or keyword-optimized version.

## Quality Checklist

Before finalizing a recommended title, verify that it:

- Contains essential keywords for searchability.
- Is concise and preferably under 20 words.
- Avoids filler and unsupported claims.
- Uses clear grammar and unambiguous modifier relationships.
- Matches the target field or journal when known.
- Accurately represents the manuscript content.
- Uses only standard abbreviations.
- Sounds natural as an English academic title.

