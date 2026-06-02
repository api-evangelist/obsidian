---
title: Goodbye legacy editor
url: https://obsidian.md/blog/goodbye-legacy-editor/
date: '2023-11-02'
author: liam
feed_url: https://obsidian.md/feed.xml
---
In the upcoming Obsidian v1.5, the legacy editor will be removed from the app. For plugin developers, this means we will be completely removing CodeMirror 5 and you will be able to assume users on newer versions of Obsidian will be using CodeMirror 6. The legacy editor has been a part of Obsidian since the beginning. In Obsidian v0.13, (which we shipped almost 2 years ago!), we completely rewrote the editor to be more robust and more future-proof. This new editor has been the default editing experience since it was introduced; however, the old editor has continued to stick around as an option. Many of Obsidian's first community plugins relied on the legacy editor so we kept it around for compatibility. As we look forward to big and better editing improvements, we've decided it's time to part ways. For most users, you likely won't notice anything different. Longer term, this will make it even easier for us to ship newer and better editing experiences . Of course, source mode will remain an option if you're looking for a strictly plain text experience.
