+++
title = "{{ replace .Name `-` ` ` }}" # use site name if it's main about page
author = {{ with .Site.Author.name }}"{{.}}"{{ else }} "" {{ end }}
date = {{ .Date }}
publications = "" # add publication name if it belongs to a publication
draft = true
image = "images/cover.png" # add cover image 

# This page content will be placed as the description.
+++

<!-- Write "about" description here! -->


