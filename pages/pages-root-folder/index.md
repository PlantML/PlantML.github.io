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
  title: "Lab news"
  url: '/about_news/'
  image: impacts_logo.png
  text: "Check out what's going on in our lab"
widget2:
  title: "Our team"
  url: '/people_current/'
  image: lab_200517.png
  text: "An energetic, fun, and collaborative group of scientists"
widget3:
  title: "Research Projects"
  url: '/research_projects/'
  image: 200601_chrisitna_tig_cover_wide.png
  text: 'Check out what the lab is working on these days.'
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
  url: "/people_join_us/"
  text: Check out position openings ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
