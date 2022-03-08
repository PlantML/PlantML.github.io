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
  title: "About us"
  url: '/about_mission/'
  image: 
  text: "What this project is about"
widget2:
  title: "Our team"
  url: '/people/'
  image: 
  text: "A highly interdisciplinary group of scientists"
widget3:
  title: "Projects"
  url: '/research_projects/'
  image: 
  text: 'Check out where we are headed in research'
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
  url: "https://www.nsf.gov/awardsearch/showAward?AWD_ID=2107215&HistoricalAwards=false"
  text: An NSF-funded project
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
