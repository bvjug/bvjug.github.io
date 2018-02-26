---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blogs"
  url: 'https://bvjug.github.io/'
  image: widget-1-302x182.jpg
  text: 'You can find the blogs for the BVJUG here and it will hold all the information about the past events and some interesting articles by the admins and users'
widget2:
  title: "Why to get involved in BVJUG?"
  url: 'https://bvjug.github.io/'
  text: 'Joining a JUG has following advantages.<br/>1. Networking <br/>2. Staying up to date with Java.<br/>3. Interesting Presentations.<br/>'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://storage.googleapis.com/gweb-uniblog-publish-prod/images/YouTube.max-2800x2800.png" width="220" height="170" alt style="height:170px; width:220px; "/></a>'
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
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/_ijM31HTodE?start=62" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
