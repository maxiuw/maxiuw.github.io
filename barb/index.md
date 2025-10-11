---
layout: nonavbar
title: For Barb
permalink: /barb/
toc: false
robots: noindex
# Change this to 10 or 15 if you prefer
autoplay_seconds: 12
---


<script>
window.BARB_SLIDES = {{ site.data.barb.slides | jsonify }};
window.BARB_AUTOPLAY_SECONDS = {{ page.autoplay_seconds | default: 12 }};
</script>


{% include barb-slideshow.html %}