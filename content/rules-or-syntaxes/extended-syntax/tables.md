+++
title = "Tables in markdown"
description = "Tables are useful for presenting data and providing a break for the reader from textual monotony"
weight = 100
+++

Markdown allows you to create and format tables using hyphens (`-`) and pipes (`|`). This section explains how to structure tables, align text, format content and handle special characters within table cells.

## Create a basic table

To create a table, use three or more hyphens **(`---`)** to define each column’s header and separate the columns with pipes **(`|`)**. While not essential, include a pipe at the beginning and end of each row for readability.

An example is provided below followed by the rendered output.

```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```
  
| Syntax | Description |
| --------- | ----------- |
| Header | Title |
| Paragraph | Text |

Note that while the cell widths may vary, the rendered output will look consistent.

Manually typing hyphens and pipes can be time-consuming. To speed things up in Obsidian, use `Insert > Table` from the command palette (accessible via `Command P`). Tools like Obsidian’s [Advanced Tables](https://obsidian.md/advanced-tables) %%note%% plugin give you even more control.

## Aligning text in tables

You can align text within table columns using colons (`:`) in the header row. The default state is left aligned:

- Left align: `:---`
- Centre align: `:---:`
- Right align: `---:`

An example is provided below followed by its rendered output.

```markdown
| Syntax | Description | Detail |
| :--- | :----: | ---: |
| Header | Title | Heading |
| Paragraph | Text | Words |
```

| Syntax    | Description |  Detail |
| :-------- | :---------: | ------: |
| Header    |    Title    | Heading |
| Paragraph |    Text     |   Words |

## Formatting text in tables

You can format text inside table cells using inline markdown elements, such as:

* **Bold** (`**bold**`)
* *Italic* (`*italic*`)
* `Code` (backticks around words or phrases)
* [Links](https://example.com).

See the [extended syntax](/rules-or-syntaxes/extended-syntax) for more advice.