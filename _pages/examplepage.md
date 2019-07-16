---
layout: onepage
title: "Test Page 1"
description: "this is the description"

exampleGallary: ["https://via.placeholder.com/1920x1080.png?text=Example+Image+2",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+3",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+4",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+5"]

---
## Sub-heading

This is the page content

Below is a single image.
{% include image.html id="example1" images="https://via.placeholder.com/1920x1080.png?text=Example+Image+1" %}

Below is a gallary of images.
{% include imageslider.html id="exampleGallary" images=page.exampleGallary %}
