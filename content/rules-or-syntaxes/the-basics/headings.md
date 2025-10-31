+++
title = "Headings in markdown"
description = "Headings are designated by simply preceding them with a hash, or number sign"
weight = 300
+++

To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading. For example, to create a heading  three (`<h3>`), use three number signs (e.g. `### Header`).

| Markdown            | HTML                  | Rendered output     |
| ------------------- | --------------------- | ------------------- |
| `# Heading  1`      | `<h1>Heading  1</h1>` | <h1>Heading  1</h1> |
| `## Heading  2`     | `<h2>Heading  2</h2>` | <h2>Heading  2</h2> |
| `### Heading  3`    | `<h3>Heading  3</h3>` | <h3>Heading  3</h3> |
| `#### Heading  4`   | `<h4>Heading  4</h4>` | <h4>Heading  4</h4> |
| `##### Heading  5`  | `<h5>Heading  5</h5>` | <h5>Heading  5</h5> |
| `###### Heading  6` | `<h6>Heading  6</h6>` | <h6>Heading  6</h6> |

Alternatively, on the line below the text, add any number of `==` characters for Heading  1 or `--` characters for Heading  2.

Markdown applications don’t agree on how to handle a missing space between the number signs (`#`) and the heading name. For compatibility, always put a space between the number signs and the heading name.

You should also put blank lines before and after a heading for compatibility.