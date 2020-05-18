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
<<<<<<< HEAD
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
=======
  title: "Research Projects"
  url: '/research_projects/'
  image: wang_figure.png
  text: 'Check out what the lab is working on these days.'
widget2:
  title: "Awesome Discoveries"
  url: 'http://www.youtube.com/watch?v=TwI1aeWz9Dc&t=0m38s'
  image: nsf_youtube_screenshot.png
  text: "NSF highlights work by the Shiu lab in their series on <i>Awesome Discoveries You Probably Didn't Hear About.</i>"
widget3:
  title: "NRT IMPACTS"
  url: 'https://impacts.natsci.msu.edu/'
  image: impacts_logo.png
  text: "In 2019 the <b>I</b>ntegrated training <b>M</b>odel in <b>P</b>lant <b>A</b>nd <b>C</b>ompu<b>T</b>ational <b>S</b>ciences NRT training grant began. Check out this innovative training program for incoming students!"
>>>>>>> parent of a3e525e... Update index.md
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
