+++
title = "The extended syntax"
description = "If you want to extend your knowledge of markdown, continue reading below"
sort_by = "weight"
weight = 20
transparent = true
template = "mdhb-listing.html"
page_template = "mdhb-single.html"
+++

Here are some of the features that may or may not be enabled by the markdown editor you end up using. That’s down to the individual developer.

Obsidian, for instance, takes a different approach when it comes to `Heading IDs`. If you want to link to a `Heading ID` in Obsidian you type the following:

```Obsidian
[[#custom-id]]
```

Alternatively, you add a plugin, such as the [Table of Contents plugin](https://github.com/hipstersmoothie/obsidian-plugin-toc), and that takes care of adding Heading IDs for you.

I have written notes explaining some of these items in more detail. These are linked to below. 

<table>
<tr>
<th>Feature</th>
<th>Syntax</th>
</tr>
<tr>
<td><a href="/tables-in-markdown">Tables</a></td>
<td>
<code>
| Feature | Description |
<br>
| ----------- | ----------- |
<br>
| Header | Title |
<br>
| Paragraph | Text |
</code>
</td>
</tr>
<tr>
<td><a href="/fenced-code-blocks-markdown">Fenced code block</a></td>
<td><pre lang="json">
```
{
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
}
```
</pre>
</td>
</tr>
<tr>
<td><a href="/footnotes-in-markdown">Footnote</a></td>
<td><code>Here’s a sentence with a footnote. [^1] 
<br>
[^1]: And the footnote.</code>
</td>
</tr>
<tr>
<td><a href="/heading-ids-in-markdown">Heading IDs</a></td><td><code>### Custom heading {#custom-id}</code></td>
</tr>
<tr>
<td><a href="/definition-lists-in-markdown">Definition list</a></td>
<td><code>term
<br>
: definition</code>
</td>
</tr>
<tr>
<td>
<a href="/task-lists-in-markdown">Task list</a></td>
<td><code>- [x] Write to John
<br>
- [ ] Send an email to Heather
<br>
- [ ] Phone Ian</code></td>
</tr>
<tr>
<td><a href="/strikethrough-in-markdown">Strikethrough</a></td>
<td><code>~~strikethrough~~</code></td>
</tr>
<tr>
<td><a href="/highlight-in-markdown">Highlight</a></td>
<td><code>This word is ==highlighted==.</code></td>
</tr>
<tr>
<td><a href="/subscript-in-markdown">Subscript</a></td>
<td><code>S~2~O</code></td>
</tr>
<tr>
<td><a href="/superscript-in-markdown">Superscript</a></td>
<td><code>z^2^</code></td>
</tr>
</table>

Some markdown editors use emojis and other symbols. I don’t use emojis, but you can find out more about them [here](https://gist.github.com/rxaviers/7360908). Wikipedia also has a list of [HTML entities](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references#List_of_character_entity_references_in_HTML) that are used.

