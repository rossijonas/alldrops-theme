+++

# | USER CUSTOM |

# Use site name if it is the website's main about page.
name = "{{ replace .Name `-` ` ` }}"
# `showName` display the site/section name at the top of about page.
showName = false
# `author` field requires the `ninckname` of the author creating the
# current page.
author = {{ .Site.Author.name | default "" }}
draft = true

+++

<!-- Write "about" description here! -->

#### Welcome to {{ replace .Name `-` ` ` }}

We're glad to have you here!
