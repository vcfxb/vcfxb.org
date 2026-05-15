+++
title = "system-memory"
description = "A tiny little crate to inspect system memory usage"
weight = 10

[extra.links]
GitHub = { url = "https://github.com/vcfxb/system-memory", icon = "github" }
"crates.io" = { url = "https://crates.io/crates/system-memory", icon = "package" }
"API Docs (latest)" = { url = "https://docs.rs/system-memory/latest/system_memory/", icon = "file-text" }
+++

The system-memory crate is a tiny little project I finished about two years ago (at time of writing), initially with the goal of teaching myself
a bit more about building cross-platform utilities that have to interface with OS dependent libraries. It exposes a system independent way
to check the host's total memory, used memory, and free memory. 
