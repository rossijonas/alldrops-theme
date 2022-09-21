+++

# | ! DO NOT CHANGE ! | 
{{ $dir := index (findRE "/posts/.*" .Dir) 0 }}
date = {{ .Date }}
lastmod = {{ .Date }}
#
# | ! DO NOT CHANGE (end) ! | 



# | USER CUSTOM |
title = "{{ replace .Name `-` ` ` | replaceRE `\d+ \d+ \d+_` `` | title }}"
subtitle = ""
# `author` and `authors` fields requires the `ninckname` of the author
# creating the current page.
author = "{{ .Site.Author.name | default "" }}"
authors = "{{ .Site.Author.name | default "" }}"
description = ""
categories = []
tags = []
# `image` param defines the arcticle's cover image.
image = "{{ $dir }}images/cover.png" 
# All article images.
images = []
# Article slug on medium.
# (Compatible with medium-to-hugo tool.)
aliases = []
imgs = []
readingTime = true  # Show reading time after article date
toc = true
comments = false
justify = false  # text-align: justify;
single = false  # display as a single page, hide navigation on bottom, like as about page.
license = ""  # CC License
draft = true

+++



![image]({{ $dir }}images/cover.png#layoutTextWidth)

