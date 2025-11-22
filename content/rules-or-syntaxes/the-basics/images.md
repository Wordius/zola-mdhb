+++
title = "Images in markdown"
description = "Adding an exclamation mark in front of the link format gets you the code necessary to show an image"
weight = 1000
path = "images-in-markdown"
+++

To include an image, add an exclamation mark (`!`), followed by alt text in brackets and the path or URL to the image in parentheses. You can also add a title in quotation marks after the path or URL.

```
![Image alt text](/img/image.jpg "Title for image")
```

## Linking images

To add a link to an image, enclose the markdown for the image in brackets, and then add the link in parentheses.

```markdown
[![Alt text for Image](/images/image.jpg "Title for image")](https://example-image-url.com/)
```

## Image size

The markdown syntax for images doesn’t allow you to specify the width and height of images. If you need to resize an image and your markdown processor supports HTML, you can use the `img` HTML tag with the `width` and `height` attributes to set the dimensions of an image in pixels.

```html
<img src="/img/image.jpg" width="500" height="300">
```

The rendered output will contain the image resized to the dimensions you specified.

## Image captions in markdown

Markdown doesn’t support image captions, but there is a workaround. If your markdown application supports HTML, you can use the `figure` and `figcaption` HTML tags to add a caption to your image.

```html
<figure>
    <img src="/images/image.jpg"
         alt="Image alt text">
    <figcaption>Caption for image</figcaption>
</figure>
```