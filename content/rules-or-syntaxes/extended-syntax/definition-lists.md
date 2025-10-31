+++
title = "Definition lists"
description = "In HTML, definition lists are described as ‘description lists’. Both refer to pairs of terms and their definitions"
weight = 500
+++

Some markdown processors support definition lists – pairs of terms and their definitions.

This is the syntax:

```markdown
Penguins
: This is the first definition of penguins.

Otters
: This is the first definition of otters.
: This is the second definition of otters.
```

And this is how the HTML will be rendered:

```html
<dl>
<dt>Penguins</dt>
<dd>This is the definition of a penguin.</dd>
<dt>Otters</dt>
<dd>This is the first definition of otters.</dd>
<dd>This is the second definition of otters.</dd>
</dl>
```

Definition lists are not directly supported by Obsidian, but there is a [plugin](https://www.obsidianstats.com/plugins/definition-list) that might be worth exploring.