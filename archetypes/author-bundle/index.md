+++
# | ! DO NOT CHANGE ! | 
# 
# The `email` param is the unique ID that identifies the author.
#
# This `email` param IS NEVER DISPLAYED on the site! It's only purpose to
# serve as author identification, fetched from user's `git config`.
# (The author email to be displayed at the site is defined at `emailAlias` 
# param.)
# 
# Make sure to set the `git config user.email` and `git config user.name` for
# your project after installing this theme (see theme docs), otherwise this
# will break.
#
# NEVER CHANGE the `git config user.email` for this repository nor the `email`
# param below.
# 
# Be aware that changing the `git config user.email` or changing `email` param
# below, after having some content already created for this site, will require
# to manually replace the user email at `author` param on post's frontmatter,
# for every post written by the user.
email = "{{ .GitInfo.AuthorEmail }}"
#
# Date of creation reflects the date author joined the site.
date = {{ .Date }}
#
# | ! DO NOT CHANGE (end) ! | 



# | CHANGE IF NEEDED | 
# 
# Changing the author name field below, will change the auhtor name in
# every single page it is shown, after next build.
name = {{ with .GitInfo.AuthorName }}"{{.}}"{{ else }} "" {{ end }}
#
# Author email is hidden by default.
emailAlias = ""
# 
# Drop your profile pic inside content/authors/<name@email.com>/images/ dir
# and replace the file name below.
avatar = "/about/{{ .GitInfo.AuthorEmail }}/images/avatar.png"
#
# Write your short bio here.
summary = "Hello, I'm Hugo, I am a passionate blogger that loves surfing and the Go programming language!"



# This page's content will be placed as the author custom description.
+++

<!-- Write about yourself here! -->

#### About me

I love reef breaks on prefect offshore wind days, I dream about stand up backside barrels everyday!

#### Carreer Achievements

I helped the development of many open-source porojects such as [alldrops-theme](
https://github.com/alldropsinfo/alldrops-theme)

