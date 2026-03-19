---
title: "Layout Tour"
date: 2026-03-18T15:30:00Z
description: "List pages, single pages and the top status line"
pageNumber: "P202"
---

The theme ships with a narrow set of layouts on purpose, and this post calls them out directly.

## Home layout

The homepage uses `content/_index.md` and prints its content immediately below the large title banner. That makes it ideal for a profile summary, contact information, or a short project index.

## Section list layout

The `posts` section uses the list template. Each entry appears as a two-column row with the publish date on the left and the title on the right.

## Single page layout

Each post page adds a `DATE` row automatically. If you provide a `description` value in front matter, it also adds an `ABOUT` row above the article body.

## Navigation links

- [Back to posts]({{< relref "/posts" >}})
- [Back to home]({{< relref "/" >}})
- [Theme repository](https://github.com/Mrchazaaa/hugo-teletext)

## Practical use

This layout set is enough for a small personal homepage, project notes, or a straightforward blog that values tone and typography over feature sprawl.
