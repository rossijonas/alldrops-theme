+++
# Create new post with the `hugo new` command: 
# `hugo new --kind post-bundle posts/<sub-section>/<YY-MM-DD>_<post-name>`

date = {{ .Date }}
lastmod = {{ .Date }}

title = "{{ replace .Name `-` ` ` | replaceRE `\d+ \d+ \d+_` `` | title }}"

subtitle = ""

# `author` field requires the ninckname of the author creating the
# current page.
author = {{ with .Site.Author.name }}"{{.}}"{{ else }} "" {{ end }}

description = ""

categories = []

tags = []

# `image` param defines the arcticle's cover image.
{{ $dir := index (findRE "/posts/.*" .Dir) 0 }}
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

