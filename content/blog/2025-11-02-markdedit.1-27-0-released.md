+++
title = "MarkEdit 1.27.0 released"
description = "MarkEdit joins the Tahoe crowd"
date = 2025-11-02
[taxonomies]
tags = ["MarkEdit", "markdown"]
+++

{{ image(path="/img/markedit-background-colors.webp", caption="MarkEdit 1.27.0 adds icon variants for dark and light mode") }}

- MarkEdit has adopted the [Liquid Glass](https://www.apple.com/newsroom/2025/06/apple-introduces-a-delightful-and-elegant-new-software-design/) aesthetics, see [settings.json](https://github.com/MarkEdit-app/MarkEdit/wiki/Customization#generaluseclassicinterface) if you'd like to switch back.
- Added icon variants for dark mode and clear/tinted mode.
- Dropped support for macOS Sonoma, see [macos-14](https://github.com/MarkEdit-app/MarkEdit/releases/tag/macos-14) for last compatible version.

On macOS Tahoe, Apple introduced an on-device AI capability called [Foundation Models](https://developer.apple.com/documentation/FoundationModels). MarkEdit now supports it via the [MarkEdit-api](https://github.com/MarkEdit-app/MarkEdit-api). Please refer to the sample extension [MarkEdit-ai-writer](https://github.com/MarkEdit-app/MarkEdit-ai-writer) to learn more.