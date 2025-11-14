+++
title = "MultiMarkdown V7 alpha released"
description = "At the age of 18(!), MultiMarkdown Composer almost reaches version 7"
date = 2025-11-14
[taxonomies]
tags = ["markdown", "MultiMarkdown Composer", "MultiMarkdown"]
+++

At the tender age of 18, having been around since 2007, MultiMarkdown Composer has ‘almost’ reached the heady heights of version 7.

From the [Fletcher Penney](https://fletcherpenney.net/2025/11/multimarkdown_7) blog:

> MultiMarkdown v7 is available on [Github](https://github.com/fletcher/MultiMarkdown-7). It is still in ‘alpha’, meaning that I am still actively testing it and developing it, and it is not feature complete yet. There is more information in the project README, but briefly:
>
>- The goal was cleaner code with better performance and cleaned up edge cases
>- HTML and LaTeX output is done, but still being tested in real use cases (as well as fuzz testing)
>- Other output formats will be implemented after HTML and LaTeX are “finalized”
>- The command line interface is revised
>- The API is revised
>
>The main incomplete step at this point is a cleaner API for retrieving the AST rather than HTML/LaTeX output. Currently it will cause memory leaks if called from another program like this. I need to decide how I want to restructure this in a simple way while maintaining performance.