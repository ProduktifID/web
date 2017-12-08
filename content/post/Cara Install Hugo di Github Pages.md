---
title: "Cara Install Hugo Di Github Pages"
date: 2017-12-08T14:10:53+07:00
lastmod: 2017-12-08T14:10:53+07:00
draft: true
keywords: [Install, Hugo, Github, Github Pages]
description: "Cara Menginstall Hugo pada Github Pages"
tags: [Hugo, Github]
categories: [Tutorial]
author: "ProduktifID"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: true
autoCollapseToc: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false
---


Berikut ini adalah command untuk menginstall Hugo pada Github Pages.
<pre>
<code>cd blog
git init
rm -rf public
git remote add origin https://github.com/ProduktifID/web.git
git add .
git commit -m ""
git push -u origin master
git submodule add -b master https://github.com/ProduktifID/produktifid.github.io.git public
hugo
cd public
git add .
git commit -m ""
git push -u origin master
</code>
</pre>
<!--more-->

<!-- Your front matter up here -->

## Introduction

One morning, when Gregor Samsa woke from troubled dreams, he found himself transformed in his bed into a horrible vermin.

## My Heading

He lay on his armour-like back, and if he lifted his head a little he could see his brown belly, slightly domed and divided by arches into stiff sections. The bedding was hardly able to cover it and seemed ready to slide off any moment.

### My Subheading

A collection of textile samples lay spread out on the table - Samsa was a travelling salesman - and above it there hung a picture that he had recently cut out of an illustrated magazine and housed in a nice, gilded frame. It showed a lady fitted out with a fur hat and fur boa who sat upright, raising a heavy fur muff that covered the whole of her lower arm towards the viewer. Gregor then turned to look out the window at the dull weather. Drops
