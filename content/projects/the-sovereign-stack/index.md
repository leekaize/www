+++
title = "The Sovereign Stack"
description = "Software stack for hosting my files, notes, websites, etc."
weight = 2
template = "page.html"

[taxonomies]
tags = ["digital"]

[extra]
local_image = "projects/the-sovereign-stack/nextcloud.webp"
+++

## Components

- [Nextcloud AIO](https://github.com/nextcloud/all-in-one) hosted on Hetzner server running Debian. It stores my files, calendar, kanban and news. [RSSHub](https://github.com/DIYgod/RSSHub) running on Nextcloud server, to generate RSS feeds from specific websites.
- [Joplin](https://github.com/laurent22/joplin) as main note taking app, everything encrypted and stored in Nextcloud through WebDAV.
- [Zola](https://github.com/getzola/zola) as static site generator for this personal website, using [tabi](https://github.com/welpo/tabi) theme.

## Criteria for Choices

- Open-source: No hidden tracking
- Self-hosted: No corporate terms of services or data mining
- Standards-based: No vendor lock-in
- Simplicity: Easy to maintain and good performance
