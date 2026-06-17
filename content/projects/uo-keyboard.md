+++
title = "Ũõ (ঙ) Keyboard"
description = "A Windows TSF IME implementing Avro Phonetic scheme"
weight = 12
date = 2026-01-02
updated = 2026-06-12

[taxonomies]
tags = ["Bangla", "IME", "Windows", "Windows TSF", "Rust"]

[extra]
gh_repo = "RagibHasin/uo-keyboard"
license = "MPL-2.0"
+++

{{ infobar() }}

It is an input method editor (IME) for Windows that implements [Avro Phonetic](https://omicronlab.com/avro-keyboard.html) and a new Khipro pseudo-phonetic scheme using Windows Text Service Framework and Rust.

It is loosely based on the [sample IME from Windows classic samples](https://github.com/microsoft/Windows-classic-samples/blob/main/Samples/IME/) and its partial [Rust port](https://github.com/saschanaz/ime-rs). Phonetic conversion uses [`okkhor`](https://github.com/gulshan/okkhor/) by [@gulshan](https://github.com/gulshan).
