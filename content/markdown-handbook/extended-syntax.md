+++
title = "Extended syntax"
description = "If you want to extend your knowledge of markdown, continue reading below"
slug = "extended-syntax"
weight = 300
+++

Here are some of the features that may or may not be enabled by the markdown editor you end up using. That’s down to the individual developer.

Obsidian, for instance, takes a different approach when it comes to `Heading IDs`. If you want to link to a `Heading ID` in Obsidian you type the following:

```Obsidian
[[#custom-id]]
```

Alternatively, you add a plugin, such as the [Table of Contents plugin](https://github.com/hipstersmoothie/obsidian-plugin-toc), and that takes care of adding Heading IDs for you.

I have written a number of posts explaining some of these items in more detail. These are linked to below. 

<table>
<tr>
<th>Feature</th>
<th>Syntax</th>
</tr>
<tr>
<td>Table</td>
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
<td>Fenced code block</td>
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
<td>Footnote</td>
<td><code>Here's a sentence with a footnote. [^1] 
<br>
[^1]: And the footnote.</code>
</td>
</tr>
<tr>
<td>Heading ID</td><td><code>### Custom heading {#custom-id}</code></td>
</tr>
<tr>
<td>Definition list</td>
<td><code>term
<br>
: definition</code>
</td>
</tr>
<tr>
<td>
Task list</td>
<td><code>- [x] Write to John
<br>
- [ ] Send an email to Heather
<br>
- [ ] Phone Ian</code></td>
</tr>
<tr>
<td>Strikethrough</td>
<td><code>~~strikethrough~~</code></td>
</tr>
<tr>
<td>Highlight</td>
<td><code>This word is ==highlighted==.</code></td>
</tr>
<tr>
<td>Subscript</td>
<td><code>S~2~O</code></td>
</tr>
<tr>
<td>Superscript</td>
<td><code>z^2^</code></td>
</tr>
</table>
