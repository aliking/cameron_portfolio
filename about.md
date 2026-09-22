---
layout: page
title: About
permalink: /about/
---

{% capture static %}
    <video autoplay muted loop playsinline style="width:100%;height:100%;object-fit:cover;">
    <source src="{{ '/assets/project_media/about/play_vid.mp4' | relative_url }}" type="video/mp4" />
    </video>
{% endcapture %}
{% include tv-frame.html id="example" media=static media_x="5%" media_y="5%" media_width="89%" media_height="72%" %}
