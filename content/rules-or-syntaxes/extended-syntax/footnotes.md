+++
title = "Footnotes in markdown"
description = "Stop your text becoming cluttered with reference-style material by adding footnotes to your copy"
weight = 300
path = "footnotes-in-markdown"
+++

Footnotes allow you to add references or notes without cluttering the main text. They are numbered automatically in the rendered output.

Add footnotes using the following syntax:

```md
This is a simple footnote example.[^1]

[^1]: This is the referenced text.
[^2]: Add two spaces at the start of each new line.
	  This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.
```

You can also inline footnotes in a sentence. Note that the caret goes outside the brackets.

```md
You can also use inline footnotes. ^[This is an inline footnote.]
```