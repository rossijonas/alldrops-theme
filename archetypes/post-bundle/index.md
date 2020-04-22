+++
title = "{{ replace .Name `-` ` ` | replaceRE `\d+ \d+ \d+_` `` | title }}"
subtitle = ""
author = {{ with .GitInfo.AuthorEmail }}["{{.}}"]{{ else }}[]{{ end }}
date = {{ .Date }}
lastmod = {{ .Date }}

description = ""

publications = "" 

categories = []

tags = []

image = "/posts/{{ .Name }}/images/cover.png" # add arcticle cover image (compatible with medium-to-hugo tool)

images = [] # all article images (compatible with medium-to-hugo tool)

aliases = [] # article slug on medium (compatible with medium-to-hugo tool)

imgs = []

readingTime = true  # show reading time after article date
toc = true
comments = false
justify = false  # text-align: justify;
single = false  # display as a single page, hide navigation on bottom, like as about page.
license = ""  # CC License
draft = true
+++



![image](/posts/{{ .Name }}/images/cover.png#layoutTextWidth)

