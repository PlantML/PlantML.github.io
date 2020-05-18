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
  title: "Lab News"
  url: '/about_news/'
  image: 200601_chrisitna-tig-cover.jpg
  text: 'What's new in our lab'
widget2:
  title: "Great People"
  url: '/people_current/'
  image: 14_lab.png
  text: "Who we are"
widget3:
  title: "Awesome Discoveries"
  url: '/research_projects/'
  image: wang_figure.png
  text: "Check out what we are working on"
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
permalink: index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
