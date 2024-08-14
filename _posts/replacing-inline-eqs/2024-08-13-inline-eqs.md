---
layout: post
title:  Replacing inline equation delimeters from Obsidian to this blog
date:   2024-08-13 14:02:00 +0000
categories: jekyll update
usemathjax: true
---

I write ALL of my notes in my Obsidian vault, and sometimes, I like to transfer my notes to my public blog for fun. However, in Obsidian, I delimit inline LaTeX equations with `$` but mathjax requires inline equations to be delimited by the `\\(` and `\\)` characters. To combat this issue of converting everytime, I decided to just replace all character sequences that follow this regex expression `\$([^$]+)\$` with `\\\($1\\\)`. I find this super helpful, and wanted to share with anyone else with this issue.