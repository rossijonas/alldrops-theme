+++
title = "{{ replace .Name `-` ` ` }}" # use site name if it's main about page
showTitle = false
author = {{ with .Site.Author.name }}"{{.}}"{{ else }} "" {{ end }}
date = {{ .Date }}
publications = "" # add publication name if it belongs to a publication
draft = true

# This page content will be placed as the description.
+++

<!-- Write "about" description here! -->


