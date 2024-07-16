---
layout: post
title: "Setting up GitHub pages w/ Jekyll"
author: Robert MacLeod III
categories: blog github jekyll
---

### GitHub Pages

Fairly simple process to get started. Navigate to [GitHub Pages](https://pages.github.com/) and follow the instructions listed. I setup
mine as an organization so I can utilize it to store all my TAFE related code. Next is the fun part.....

### Jekyll

[Jekyll](https://jekyllrb.com/) is one of the recomended methods for managing you GitHub Pages site. Your mileage may very but I use Arch Linux (EndeavourOS)
so let the fun begin. Their [Quick Start Guide](https://jekyllrb.com/docs/) is pretty good to be fair but Arch btw can have its quirks being on
the bleeding edge. Jekyll runs on Ruby which has it's own "package manager" called gems.

Most of my issues derived from trying to get jekyll to run initially.
When I was installing items usings gems it gave me a warning telling me that my $PATH was incorrect and listed the correct path. After reviewing the install
procedure i just swapped the listed path in the procdure to the one listed in the error. This fixed all my issues with Jekyll. After that was sorted everything
was fairly simple and the Jekyll documentation is indepth and easy to follow. Now I've got a blog.
