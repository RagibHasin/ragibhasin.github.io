+++
title = "Data Importer TUI"
description = "A TUI for importing large data into a web system"
weight = 98
date = 2017-10-03

[taxonomies]
tags = ["data", "TUI", "NodeJS", "JavaScript", "Rust"]
+++

It was a data entry and import solution to a government data management system, that has been designed and used internally.

Web UI of the target system was very cumbersome and slow, 3-5x slower than one-by-one entry with the TUI, up to 10x slower when doing bulk upload. This lead to me designing and optimizing it for easier data entry first in JavaScript using NodeJS and later using Rust.

Its working procedure involved:

1. Logging into the service
2. Composing a HTTP POST request for a new data
3. Appropriately fetching and displaying the captcha in command line
4. Submitting the captcha

This data importer took approximately 25 person-hours of development and maintenance time and saved about 65 hours in usage, netting on 40 hours saved in total.

This project was a proprietary one and is no longer maintained.
