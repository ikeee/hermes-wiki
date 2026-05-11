# Wiki Schema

## Domain
通用知识库 — 涵盖技术、AI、教育、运维等话题。

## Conventions
- File names: lowercase, hyphens, no spaces
- Every wiki page starts with YAML frontmatter
- Use [[wikilinks]] to link between pages
- Every new page added to index.md
- Every action appended to log.md

## Frontmatter
```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary
tags: [tag1, tag2]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy
- tech: tool, framework, language, hardware
- ai: model, llm, training, inference
- edu: teaching, school, resource
- ops: devops, server, network
- meta: concept, comparison, note

## Page Thresholds
- Create page when entity/concept appears in 2+ sources
- Don't create for passing mentions
- Split pages over 200 lines
