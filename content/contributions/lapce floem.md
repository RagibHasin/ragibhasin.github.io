+++
title = "lapce/floem"
date = "2023-05-01"

[taxonomies]
tags = ["GUI", "reactive", "Rust"]

[extra]
gh_repo = "lapce/floem"
+++

Floem is a native cross-platform Rust UI library with fine-grained reactivity inspired by [Leptos](https://leptos.dev/).

It is the UI library that powers the [Lapce](https://lap.dev/lapce/) code editor.

I fixed non-standard text input behavior on Windows when using non-standard input method editors (IME) that hooks keyboard events directly, like [Avro Keyboard](https://omicronlab.com/avro-keyboard.html) which I used heavily at that time.

However, I've switched to my [homegrown replacement](@/projects/uo-keyboard.md) of it that uses proper IME framework.
