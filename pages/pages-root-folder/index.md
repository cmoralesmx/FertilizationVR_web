---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: FertilizationVR_header.jpg
widget1:
  title: "Promo Video"
#  url: 'http://phlow.github.io/feeling-responsive/blog/'
#  image: promo_btn.jpg 
  text: 'Our promotional video presenting a user experiencing the fertilization process at the cell-level scale in virtual reallity.'
  video: '<a href="#" data-reveal-id="videoModal1"><img src="http://cmoralesmx.github.io/FertilizationVR_web/images/promo_btn.jpg" width="302" height="182" alt=""/></a>'
widget2:
  title: "Demonstration 1"
#  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: demo1_btn.jpg
  text: '<em>FertilizationVR</em> is heavily interactive.<br/>1. Educational<br/>2. Virtual Reality.<br/>3. Immersive experience.'
  video: '<a href="#" data-reveal-id="videoModal2"><img src="http://cmoralesmx.github.io/FertilizationVR_web/images/demo1_btn.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Demonstration 2"
#  url: 'https://github.com/Phlow/feeling-responsive'
  image: demo2_btn.jpg
  text: '<em>FertilizationVR</em> is developed in-house using proven technologies. We build up on the expert knowledge of world-leading researchers in the field of Fertility and Simulation.'
  video: '<a href="#" data-reveal-id="videoModal3"><img src="http://cmoralesmx.github.io/FertilizationVR_web/images/demo2_btn.jpg" width="302" height="182" alt=""/></a>'
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
  url: /contact
  text: Get in contact to request more information ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal1" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/aFYGQIrNnRc" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModal2" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/j1uyKGSBkKQ" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModal3" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/WYAOAkYxcDo" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
