---
title: "Quartz"
---

A tool for publishing [Obsidian](notes/obsidian) to the web, and what I'm using for this note you're reading now!

It's built on top of [[Hugo SSG]].


- [Official website](http://quartz.jzhao.xyz/)
- [Github](https://github.com/jackyzha0/quartz)

## Examples

- Brandon Boswell's [digital garden](https://brandonkboswell.com/)
- Jacky's [personal notes](https://jzhao.xyz/)

## Obsidian features it supports:

Footnotes[^1]

> Blockquotes



## Obsidian features it does not:

**Generic wikilinks**. Obsidian allows you to refer to a note without mentioning its path, such as `[[software engineering]]`. Quartz requires you to use Markdown links `[]()`, with a full path and URL encoding of spaces.

Comments: `%% Typing something like this will appear in the published notes %%`

Callouts `> [!quote]`

## Drawbacks
- Significant technical knowledge needed. I had to install [[Golang]], Hugo, Make, add those to my environment path, just to build the website locally, and I still haven't published yet. 
- no RSS

[^1]: This is a footnote