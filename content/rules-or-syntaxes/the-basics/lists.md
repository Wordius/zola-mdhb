+++
title = "Lists in markdown"
description = "Lists come in a number of forms, but in this cheat sheet we are only concerned with ordered and unordered lists"
weight = 600
path = "lists-in-markdown"
+++

You can organise items into ordered and unordered lists.

## Ordered lists

To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```markdown
1. First list item
2. Second list item
3. Third list item
```

CommonMark and a few other lightweight markup languages let you use a parenthesis (`)`) as a delimiter (e.g. `1) First item`), but not all markdown applications support this. So, from a compatibility perspective or if you expect to switch editors any time soon, use periods only.

## Unordered lists

To create an unordered list, add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front of line items. Indent one or more items to create a nested list.

```markdown
- First list item
- Second list item
- Third list item
```

Or use all three methods of creating an unordered list:

```markdown
- First list item
* Second list item
+ Third list item
```

There are a couple of other list formats dealt with under the extended syntax:

- [definition lists](/rules-or-syntaxes/extended-syntax/definition-lists)
- [task lists](/rules-or-syntaxes/extended-syntax/task-list).