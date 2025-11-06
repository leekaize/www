+++
title = "[contrib] tabi"
description = "Improve simplicity of building personal website"
weight = 2
template = "page.html"

[taxonomies]
tags = ["digital", "community", "impact"]

[extra]
local_image = "projects/tabi-contrib/tabi.webp"
+++

I tried Jekyll with al-folio. Tried Material for MkDocs.

Both claimed "ease of use." but both didn't deliver.

Setup fought me. Maintenance fought me. Codebases sprawled everywhere. I'd spend hours tinkering with configs when I should've been writing.

Personal website should be place to share. Not place to waste time.

## What Changed

Found tabi. Zola-based. Static site generator in Rust.

Simple architecture. Packed with what I needed. Nothing I didn't.

Respects readers by default. Fast loads. Accessible navigation. Zero tracking. No bloat.

You're looking at it now.

## Why I Contribute

[Example of my PR](https://github.com/welpo/tabi/pull/579).

Someone else opened the issue. I picked it up.

Why was it easy?

Oscar documents everything. Builds respectful environment for contributors. Codebase makes sense. You know where things are.

Not intimidating like other static site generators. Simple. Works. Embraces community.

This also leads to me opening a [discussion to initiate a community](https://github.com/welpo/tabi/discussions/580) around tabi ecosystem.

## What You Get

Fast site that loads in milliseconds. Accessible by default. Privacy-respecting. One config file controls everything.

Write. Publish. Done.

No fighting dependency hell. No debugging mysterious build failures. No maintenance overhead.

## Try It

Start your repository by using [tabi-start template](https://github.com/welpo/tabi-start).

Only need on command to see it running:

```bash
zola serve
```

Check my implementation: [github.com/leekaize/www](https://github.com/leekaize/www)

**Your move:** Clone it. Run it. See if it fits.

---

*Tools should get out of your way. Tabi does.*