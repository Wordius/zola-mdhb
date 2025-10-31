+++
title = "Heading IDs in markdown"
description = "Heading IDs are useful when a section of text gets lengthy, allowing the reader to find their way"
weight = 400
+++

Custom IDs allow you to create linkable headings and style them with CSS.

Add the custom ID in curly braces `{#id}` after the heading text:

```markdown

### Heading {#heading-id}

```

This is the rendered HTML that will produce:

```html

<h3 id="custom-id">Some heading</h3>

```

You can link directly to headings using their custom IDs.

| Markdown                    | HTML                                   | Rendered output                      |
| --------------------------- | -------------------------------------- | ------------------------------------ |
| `[Heading ID](#heading-id)` | `<a href="#heading-id">Heading ID</a>` | <a href="#heading-id">Heading ID</a> |

Other sites can link to your heading using the full URL plus the ID.

## Obsidian

In Obsidian’s documentation there is no reference to ‘Heading IDs’. Instead, it discusses a [link to a heading in a note](https://help.obsidian.md/links#Link+to+a+heading+in+a+note).