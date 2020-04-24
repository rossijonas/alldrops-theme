+++
# Create new author with the `hugo new` command: 
# `hugo new --kind author-bundle authors/<nickname>`

# | ! DO NOT CHANGE ! | 
# 
# The `nickname` param is the unique ID that identifies the author. Please
# NEVER CHANGE the `nickname` param below.
# 
# Be aware that changing the `nickname` param below, after having some
# content already created for this site, will require to manually replace
# the user nickname at `author` param on every content already created by
# the user (posts, about pages, site config, etc).
nickname = "{{ .Name }}"
#
# Date of creation reflects the date author joined the site.
date = {{ .Date }}
#
# | ! DO NOT CHANGE (end) ! | 



# | USER CUSTOM |

fullName = ""
email = ""
website = ""

# Drop your profile pic inside `content/authors/<nickname>/images/`
# directory and replace the file name below.
avatar = "/authors/{{ .Name }}/images/avatar.png"

# Write your short bio here.
bio = "Hello, I'm Hugo, I am a passionate blogger who loves surfing and the Go programming language!"

# Social neworks.
[params.social]
  twitter = "https:/twitter.com"

+++
