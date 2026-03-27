+++
title = "Scrolled Quran"
description = "A horizontally scrolling Quran reader app"
weight = 10
date = 2026-02-15

[taxonomies]
tags = ["Islam", "Quran", "app", "GUI", "Rust"]

[extra]
gh_repo = "RagibHasin/scrolled-quran"
license = "Apache-2.0"
+++

{{ infobar() }}

It is a Quran reader app that automatically scrolls the text for hands-free, uninterrupted recitation.

I built it mainly for personal use in Ramadan of 1447 AH, and did two full recitation of the Holy Quran using this.

It uses resources from the [Quranic Universal Library (QUL)](https://qul.tarteel.ai) by Tarteel.ai, in particular the [DigitalKhatt](https://digitalkhatt.org) font by Dr. Amine Anan which is a digitized replica of the calligraphy by Master Calligrapher Uthman Taha in the 1441H mushaf from King Fahad Glorious Quran Printing Complex.

This project is written in Rust using [Xilem](https://github.com/linebender/xilem) GUI library from [Linebender](https://linebender.org/) and brought the opportunity for a few community contributions, involving the [`understory`](https://github.com/endoli/understory) crates.
