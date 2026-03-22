---
title: "Formatting Showcase"
date: 2026-03-19T09:00:00Z
description: "Headings, tables, lists, links and general body copy"
pageNumber: "201"
---

This page is a compact reference for the Markdown elements the theme styles most clearly.

## Paragraphs

Regular body text stays on the dark background, uses the Mode 7 inspired font, and keeps the theme's uppercase presentation. Inline links such as [return to the homepage]({{< relref "/" >}}) and [visit Hugo](https://gohugo.io/) inherit the accent colours.

## Table example

| Field | Example |
| --- | --- |
| Status | On air |
| Edition | Evening build |
| Output | Static files |
| Content type | Markdown |
| Link style | Bright magenta turning yellow on hover |

## Unordered list

- Fast to read.
- Easy to author.
- Distinctive without extra components.

## Ordered list

1. Write Markdown.
2. Run `hugo`.
3. Open the generated site.

## Code block

```toml
baseURL = "https://example.com/"
languageCode = "en-gb"
theme = "hugo-teletext"

[params]
pageNumber = "P100"
enableScanlines = true
```

## Secondary heading

### Small heading

The stylesheet keeps all heading levels visually consistent, which fits the teletext presentation and avoids oversized type inside the content panel.
