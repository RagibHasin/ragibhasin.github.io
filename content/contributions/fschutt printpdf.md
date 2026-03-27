+++
title = "fschutt/printpdf"
date = "2023-03-09"

[taxonomies]
tags = ["PDF rendering", "Rust"]

[extra]
gh_repo = "fschutt/printpdf"
+++

`printpdf` is a Rust library for creating, reading, writing and rendering PDF documents.

I has been intending to use this library to render some PDF documents, but found some issues with how it rendered complex-script texts.

I brought this codebase up to Rust 2018 edition in anticipation of improving the text rendering issue, but found out about [Typst](https://typst.app) at the same time.

Thus that sadly remains my only contribution to this codebase.
