+++
title = "Docsify – what is it?"
description = "Docsify is a site generator, best suited to creating documentation sites. Give it a try and you will be impressed"
date = 2025-11-24
[taxonomies]
tags = ["markdown", "static site generator", "Docsify"]
+++

{{ image(path="/img/docsify-opener.webp", caption="Docsify is a documentation site generator") }}

Docsify is a documentation site generator, but not in the traditional sense. Normally, a site generator, commonly known as a static site generator, involves downloading and installing some software. Then you have to configure it – templates, config files, etc. – adding your instructions and uploading the documents, whether directly or via GitHub or similar, to your server. Sounds like a bit of a pfaff to me.

Docsify does away with most of this. Unlike a traditional static site generator, it does not generate static html files. Instead, it loads and parses your markdown files and displays them as a website. 

Here is how it works.

The install is quite straightforward. It is recommended to install `docsify-cli` globally, which helps to initialise and preview the website locally. Open Terminal, or your command line interface, and type:

```bash
npm i docsify-cli -g
```

Then, if you want to write the documentation in the `./docs subdirectory`, use the `init` command.

```bash
docsify init ./docs
```

After the `init` is complete, you can see the following file list in the `./docs` subdirectory.

- `index.html` is the entry file
- `README.md` is the homepage
- `.nojekyll`, which prevents GitHub Pages from ignoring files that begin with an underscore.

You can update the documentation in `./docs/README.md` and, of course, you can add [more pages](https://preview.docsifyjs.org/#/adding-pages). Then preview your site by running the local server with `docsify serve` and view it at `http://localhost:3000`.

```bash
docsify serve docs
```

And this, or similar, is what you get. All I did was add an ‘About’ page and linked to it from the homepage (`README.md`).

{{ image(path="/img/docsify-example-site.webp", caption="Add any pages you want, link to them from the homepage and the default theme looks like this") }}

You can then [deploy it on GitHub Pages](https://docsify.js.org/#/deploy), share your thoughts with your ‘team’, incorporate any changes they suggest, then upload it to the world.

There are many other things you can do with Docsify, such as adding a sidebar and changing themes. The [docs](https://preview.docsifyjs.org/#/quickstart) provide you with a full explanation of how to use Docsify.

