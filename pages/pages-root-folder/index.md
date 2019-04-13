---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_dna_art.jpg
widget1:
  title: "Research Projects"
  url: '/research_projects/'
  image: widget-1-302x182.jpg
  text: 'Check out what the lab is working on these days.'
widget2:
  title: "Awesome Discoveries"
  url: 'http://www.youtube.com/watch?v=TwI1aeWz9Dc&t=0m38s'
  image: nsf_youtube_screenshot.png
  text: "NSF highlights work by the Shiu lab in their series on Awesome Discoveries You Probably Didn't Hear About"
widget3:
  title: "Awesome Discoveries"
  url: 'http://www.youtube.com/watch?v=TwI1aeWz9Dc&t=0m38s'
  image: nsf_youtube_screenshot.png
  text: "NSF highlights work by the Shiu lab in their series on Awesome Discoveries You Probably Didn't Hear About"
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: "/people_join_us/""
  text: Check out student and post-doc openings ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---