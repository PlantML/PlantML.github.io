---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_tree.png
widget1:
  title: "Research Projects"
  url: 'https://shiulab.github.io/research/projects/'
  image: widget-1-302x182.jpg
  text: 'Check out what the lab is working on these days.'
widget2:
  title: "Awesome Discoveries"
  url: 'http://www.youtube.com/watch?v=TwI1aeWz9Dc&t=0m38s'
  image: nsf_youtube_screenshot.png
  text: 'NSF highlights work by the Shiu lab in their series on Awesome Discoveries You Probably Didn't Hear About'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
  url: https://shiulab.github.io/people_join_us/
  text: Check out student and post-doc openings ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  
  <p> test</p>
</div>
