+++
title = "Links in markdown"
description = "The humble link"
weight = 900
path = "links-in-markdown"
+++

Links are important elements in Markdown for connecting content. Mastering various link syntaxes makes your documents more connected and practical.

## Basic link 

Create a link using the `[link text](URL)` format:

```
This is a link to [Google](https://www.google.com).
Visit [GitHub](https://github.com) to see open source projects.
```

Which renders as:

This is a link to [Google](https://www.google.com/). Visit [GitHub](https://github.com/) to see open source projects.

Add a title after the URL, which will appear on hover:

```
This is a [link with a title](https://www.example.com "The link title").
```

Which renders as:

This is a [link with a title](https://www.example.com/ "This is the link title").

## Reference-style links 

Separate link definition from usage:

```
This is a [reference link][1].
This is another [reference link][link-name].

[1]: https://www.example.com
[link-name]: https://www.google.com "Google Search"
```

Which renders as:

This is a [reference link](https://www.example.com/). This is another [reference link](https://www.google.com/ "Google Search").

The link text itself is used as the label:

```
Visit [Google][] to search.
See projects on [GitHub][].

[Google]: https://www.google.com
[GitHub]: https://github.com
```

Which renders as:

Visit [Google](https://www.google.com/) to search. See projects on [GitHub](https://github.com/).

## Autolinks 

Simply type the URL, wrapped in angle brackets:

```
<https://www.example.com>
<https://github.com>
```

Which renders as:

[https://www.example.com](https://www.example.com/)[https://github.com/user/repo](https://github.com/user/repo)

You can also include email addresses as autolinks: 

```
Contact me: <user@example.com>
Support: <support@company.com>
```

Which renders as:

Contact me: [user@example.com](mailto:user@example.com) Support: [support@company.com](mailto:support@company.com)

## Internal Links 

### Anchor Links 

Link to a heading on the same page:

```
Jump to [Basic Link Syntax](#basic-link-syntax)
See [Best Practices](#best-practices)
```

Which renders as:

Jump to [Basic Link Syntax](https://www.markdownlang.com/basic/links.html#basic-link-syntax) See [Best Practices](https://www.markdownlang.com/basic/links.html#best-practices)

### Relative path links 

Link to other files:

```
See [Heading Syntax](headings.md)
Back to [Home](../index.md)
```

## Special links 

### Image links 

Wrap an image in a link:

```
[![Alt text](image.png)](https://www.example.com)
```

### Download links 

Link to file downloads:

```
Download [User handbook](files/handbook.pdf)
Get [Sample Code](examples/demo.zip)
```