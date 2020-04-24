+++
# Create new posts's subsection with the `hugo new` command: 
# `hugo new --kind post-subsection-bundle posts/<sub-section>`

# Section name.
name = "{{ replace .Name `-` ` ` }}"

# Section slogan.
slogan = "(Section custom slogan here!)"

# `logo` param defines the section main logo displayed at section header,
# and at the top navigation header (reduced header).
#
# The template  works better with rectangle images.
{{ $dir := index (findRE "/posts/.*" .Dir) 0 }}
logo = "{{ $dir }}images/logo.png"

# `favicon` is the section small logo displayed at post's metadata when a 
# post is displayed outside the section it belongs to.
#
# The image must be a perfect square in order to fit the template layout.
favicon = "{{ $dir }}images/favicon.png"

# `color` param defines the section highlight color.
#
# It is a user defined color softly apllied on some minor layout parts of
# the pages that belongs to the section.
# 
# It it supposed to bring a light personallized theme change, in order to
# characterize the section.
# 
# Use any kind of color parameter accepted in CSS. (If it's empty, it
# defaults to a light grey.)
color = ""

+++
