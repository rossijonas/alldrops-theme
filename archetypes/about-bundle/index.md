+++
# Create new about page with `hugo new` command: 
# `hugo new --kind about-bundle about/<name>`

# `name` is the site or section name that this about page belongs to.
# 
# When creating the page with the `hugo new` command, make sure the
# <name> field is cased exactly as the site/section name, (example
# `posts/MY-Section` to match `MY Section` post's subsection). 
# 
# Use site name if it is the website's main about page.
name = "{{ replace .Name `-` ` ` }}"

# `showName` display the site/section name at the top of about page.
# 
# Is is useful when the site/section does not use an image as the logo.
showName = false

# `author` field requires the ninckname of the author creating the
# current page.
# 
# It is used to define the site owner or the section owner.
author = {{ with .Site.Author.name }}"{{.}}"{{ else }} "" {{ end }}

draft = true

# This page content will be placed as the description.
+++

<!-- Write "about" description here! -->

#### Welcome to {{ replace .Name `-` ` ` }}

We're glad to have you here!
