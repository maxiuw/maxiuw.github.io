---
layout: nonavbar
title: For Barb
permalink: /barb/
toc: false
robots: noindex
autoplay_seconds: 22
---


<script>
window.BARB_SLIDES = {{ site.data.barb.slides | jsonify }};
window.BARB_AUTOPLAY_SECONDS = {{ page.autoplay_seconds | default: 12 }};
</script>


{% include barb-slideshow.html %}
