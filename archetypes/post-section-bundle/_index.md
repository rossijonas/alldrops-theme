+++

# | ! DO NOT CHANGE ! | 
{{ $dir := index (findRE "/posts/.*" .Dir) 0 }}
isSection = true
sections = "{{ replace .Name `-` ` ` }}"
#
# | ! DO NOT CHANGE (end) ! | 



# | USER CUSTOM |

name = "{{ replace .Name `-` ` ` }}"
slogan = "(Section custom slogan here!)"
# `logo` fits better if it's a rectangle shape.
logo = "{{ $dir }}images/logo.png"
# `favicon` must be a perfect square in order to fit the theme layout.
favicon = "{{ $dir }}images/favicon.png"
# `color` is section's highlight (like a theme), use css compatible
# color property.
color = ""

+++
