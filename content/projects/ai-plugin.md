+++
title = "Adobe Illustrator Plugin Framework"
description = "A framework to write plugins for Adobe Illustrator in Rust"
weight = 30
#date = 2021-05-24

[taxonomies]
tags = ["Adobe", "Adobe Illustrator", "framework", "plugin", "Rust"]

[extra]
gh_repo = "RagibHasin/ai_plugin"
license = "AGPL-3.0"
is_archived = true
+++

{{ infobar() }}

It was a framework for creating plugins for Adobe Illustrator in idiomatic Rust.

I started this when my first attempt to make an Adobe Illustrator plugin for [spline](https://github.com/raphlinus/spline) in C++ failed, mostly because I didn't grasp C++ memory management and manual lifetime tracking well at the time, which caused data race and memory corruption all over the place.

This framework was born from the frustration of that failure and while I succeeded in making a (mostly) functional plugin for the curve exploration, the curve exploration itself [moved on] to new direction and thus the plugin has not been published yet.
