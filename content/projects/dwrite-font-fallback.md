+++
title = "DirectWrite Font Fallback Override"
description = "A Windhawk mod to override font fallbacks of DirectWrite"
weight = 15
date = 2025-12-17

[taxonomies]
tags = ["Reverse Engineering", "Windhawk", "Windhawk mod", "COM", "C++"]

[extra]
gh_repo = "RagibHasin/wh-dwrite-font-fallback-override"
license = "MIT"

[extra.links]
"Windhawk Mods" = "https://windhawk.net/mods/dwrite-font-fallback-override"
+++

{{ infobar() }}

It is a Windhawk mod that hooks into font fallback selection and text formatting routines of DirectWrite engine to change fallback font for any Unicode character the user chooses.

This is a result of being frustrated with default Bangla font (Nirmala UI) and wishing to learn more about COM archiecture.

Incidentally, it was my first (mostly) positive interaction with AI chatbots, as the first iteration of this mod has been created by Claude.
