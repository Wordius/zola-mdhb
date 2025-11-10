+++
title = "MarkEdit 1.27.0 released"
description = "MarkEdit joins the Tahoe crowd"
date = 2025-11-02
[taxonomies]
tags = ["MarkEdit", "markdown"]
+++

{{ image(path="/img/markedit-background-colors.webp", caption="MarkEdit 1.27.0 adds icon variants for dark and light mode") }}

MarkEdit now supports the [Liquid Glass](https://www.apple.com/newsroom/2025/06/apple-introduces-a-delightful-and-elegant-new-software-design/) look. You can use [settings](https://github.com/MarkEdit-app/MarkEdit/wiki/Customization#generaluseclassicinterface) to switch back if you don’t like that approach.

The current version has added icon variants for dark mode and clear mode, but it has also dropped support for MacOS Sonoma. See [macos-14](https://github.com/MarkEdit-app/MarkEdit/releases/tag/macos-14) for the last compatible version available.

On MacOS Tahoe, Apple also introduced an on-device AI capability called [Foundation Models](https://developer.apple.com/documentation/FoundationModels). MarkEdit now supports it via its [API](https://github.com/MarkEdit-app/MarkEdit-api). Refer to the sample extension [MarkEdit-ai-writer](https://github.com/MarkEdit-app/MarkEdit-ai-writer) to learn more.