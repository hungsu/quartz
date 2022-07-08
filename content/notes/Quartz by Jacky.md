---
title: "Quartz"
---

A tool for publishing [Obsidian](notes/obsidian) to the web, and what I'm using for this note you're reading now!

It's built on top of [Hugo](notes/Hugo), which is very fast, but can be hard to use. 

- [Official website](http://quartz.jzhao.xyz/)
- [Github](https://github.com/jackyzha0/quartz)

## Examples

- Brandon Boswell's [digital garden](https://brandonkboswell.com/)
- Jacky's [personal notes](https://jzhao.xyz/)

## Obsidian features it supports:

**Footnotes**. Click the 1 to read it! [^1]

> **Blockquotes** but



## Obsidian features it does not:

**Generic wikilinks**. Obsidian allows you to refer to a note without mentioning its path, such as `[[software engineering]]`. Quartz requires you to use Markdown links `[]()`, with a full path and URL encoding of spaces. Attempting to use wikilinks anyway seems to break links and backlinks. 

**Comments**. `%% Typing something like this will appear in the published notes %%`

**Callouts**. Typing `> [!quote]` won't make a fancy callout. You'll have to use a regular blockquote and add a symbol yourself. 

## Drawbacks
- Significant technical knowledge needed. I had to install [[Golang]], Hugo, Make, add those to my environment path, just to build the website locally. For the tech savvy it doesn't feel like much, but this is too difficult for many people. 
- No RSS. This isn't too big a deal as I don't have any readers now, but providing an RSS feed is a way to protest the overwhelming strength and evil of social media and corporate-funded news. 

[^1]: This is a footnote! Click the curled arrow to go back up