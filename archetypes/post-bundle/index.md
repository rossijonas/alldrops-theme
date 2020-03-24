+++
title = "{{ replace .Name `-` ` ` | title }}"
subtitle = ""
author = {{ with .Site.Author.name }}{{.}}{{ else }} "" {{ end }}
date = {{ .Date }}
lastmod = {{ .Date }}

description = ""

categories = []

tags = []

image = ""

images = []

imgs = []

aliases = []

readingTime = true  # show reading time after article date
toc = true
comments = false
justify = false  # text-align: justify;
single = false  # display as a single page, hide navigation on bottom, like as about page.
license = ""  # CC License
draft = true
+++

