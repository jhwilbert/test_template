---
layout: post
title:  "My first sketch"
date:   2013-12-02 14:42:59
categories: jekyll update
video_url: http://www.youtube.com/embed/fyY9tb8Rvlk
---

{% if page.video_url %}
     <div class="less-fancy-video-header">
       <iframe
         class="yt-embed"
         src="{{ page.video_url }}?&rel=0&showinfo=0&autohide=1&hd=1&wmode=transparent"
         frameborder="0"
         allowfullscreen="true"
         ></iframe>
     </div>
{% endif %}