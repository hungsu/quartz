---
title: "Quartz"
---

A tool for publishing [Obsidian](notes/obsidian) to the web, and what I'm using for this note you're reading now!

It's built on top of [Hugo](notes/Hugo), which I'm told is very fast, but can be hard to use. So far I've observed builds with this tool taking around 40 seconds which is a bit slower than I'd like. My previous tool used Jekyll and took around 20 seconds.

The [Official Quartz website](http://quartz.jzhao.xyz/) has the instructions I followed to make this.

## Obsidian features it supports:

**Footnotes**. Click the 1 to read it! [^1]

> **Blockquotes** but they're not quite the same.<br />
> For example, this is on a new line, but only because I manually added a `<br>`



## Obsidian features it does not:

Inline tags, like #claim. This will just appear as plain text. I requested support for these in [this ticket](https://github.com/jackyzha0/quartz/issues/161).

**Generic wikilinks**. Obsidian allows you to refer to a note without mentioning its path, such as `[[software engineering]]`. Quartz requires you to use Markdown links `[]()`, with a full path and URL encoding of spaces. Attempting to use wikilinks anyway will result in broken links and backlinks.

**Comments**. `%% Typing something like this will appear in the published notes as plain text %%`

**Callouts**. Typing `> [!quote]` won't make a fancy callout. You'll have to use a regular blockquote and add a symbol yourself. Someone has already requested support for these in [this ticket](https://github.com/jackyzha0/quartz/issues/80).

## Drawbacks
- Significant technical knowledge needed. I had to install [[Golang]], Hugo, Make, add those to my environment path, just to build the website on my Windows laptop. For the tech savvy it doesn't feel like much, but this is too difficult for many people. 
- No RSS. This isn't too big a deal as I don't have any readers now, but providing an RSS feed is a way to protest the overwhelming strength and evil of social media and corporate-funded news. Jacky has teased the idea of possibly adding it in future, on the Quartz Discord.

## Perks, or why I chose Quartz over everything else

All the words above may seem like I dislike Quartz. They only mean I know its weaknesses, and Quartz remains my preferred method for publishing notes despite the alternatives! 

- **Separate note titles, filenames, and link text**. One of the solutions I tried previously, Foam Research, required that note titles, filenames, and link text all be the same, and in a particular format. For instance, a Quartz link can have [any text that I desire](My%20favourite%20blogs), but a Foam link always looks like: [my-favourite-blogs](My%20favourite%20blogs), including the dashes. This was maddening!
- **Interactive graph**. The graph you see at the bottom of the page is much more friendly than others I've tried so far, with nice hover effects, bouncy physics, and even links between neighbours!
- **Dark mode**. I often read my own notes at night, and appreciate being able to set the theme to dark mode.
- **Backlinks with context**. If you look at the bottom of this page you will see some backlinks that appear to have no context. But if you hover over the backlink, you'll see the sentence that refers to this page. This is amazing! [Backlinks should include context](notes/Backlinks%20should%20include%20context)!

## Alternatives I didn't like, but you might

- [[Obsidian Publish]], but people seem to have mixed things to say about it.
- [Jekyll](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll). These notes you're reading used to be published this way. There are other ways to use Jekyll, but the method I linked seems to be the most comprehensive.

[^1]: This is a footnote! Click the curled arrow to go back up