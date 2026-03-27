+++
title = "Adhaan"
description = "A library for calculating prayer times in Rust"
weight = 15
date = 2021-05-24

[taxonomies]
tags = ["Islam", "utility", "library", "Rust"]

[extra]
gh_repo = "RagibHasin/adhaan"
license = "MIT"

[extra.links]
"Crates.io" = "https://crates.io/crates/adhaan"
+++

{{ infobar() }}

It is a Rust library for calculating prayer times. It originally started as a fork of [`salah`](https://github.com/insha/salah), which I and have been using for making a GUI and [Azzam S.A.] was using to make a TUI, but has been causing us lots of pain.

`salah` was ported to Rust by Farhan Ahmed from [Adhan](https://github.com/batoulapps/Adhan) by BatoulApps. May Allah grant him bountiful rewards.

Key differences between `salah` and `adhaan` are:

1. `adhaan` extensible in regard of calculation method.
2. `adhaan` uses `jiff` for its date-time vocabulary, in stead of `chrono`.

Motivation for this arose when I started to work on [AdhaanGUI] and although whereas AdhaanGUI itself is on hiatus, I use both `adhaan` and AdhaanGUI frequently.
