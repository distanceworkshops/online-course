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
  title: "Prep for online course"
  url: 'http://erex.github.io/feeling/blog/'
  image: widget-1-302x182.jpg
  text: 'This course will be a mix of lectures, exercises and computer practicals.'
widget2:
  title: "Take the online course"
  url: 'http://erex.github.io/feeling/chapters/'
  text: 'The content of the workshop is broken into chapters. Each chapter will take several hours to complete.'
#  video: '<a href="#" data-reveal-id="videoModal"><img src="http://erex.github.io/feeling/images/teaser-image2.png" width="302" height="182" alt=""/></a>'
        <video width="302" height="302" controls loop autoplay>
            <source src="https://www.youtube.com/watch?v=fVTmRzpD9Aw" type="video/mp4">
        </video>
widget3:
  title: "Where to learn more"
  url: 'https://erex.github.io/feeling/more-resources/'
  image: widget-github-303x182.jpg
  text: 'This online workshop does not include all material you will need to be proficient at designing, conducting and analysing a distance sampling project.  Here we show you where to acquire additional resources.'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/watch?v=fVTmRzpD9Aw" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
