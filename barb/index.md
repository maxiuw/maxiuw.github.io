<style>
/* Hide the top navbar only on this page */
nav.navbar,
header.site-header,
#navbar { display: none !important; }

/* Remove the extra top spacing left by the fixed navbar */
body { padding-top: 0 !important; }
main, .page-content, .content { margin-top: 0 !important; padding-top: 0 !important; }
</style>
---
layout: page
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