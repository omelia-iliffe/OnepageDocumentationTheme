---
onepage-id: 1
title: "Another Page"
description: "with description as well"

nav-color: customcolor1 #Oooh a fancy custom colour!

exampleGallery: ["https://via.placeholder.com/1920x1080.png?text=Example+Image+2",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+3",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+4",
                "https://via.placeholder.com/1920x1080.png?text=Example+Image+5"]


---
## Sub-heading

This is the page content

**This page is special cause it has a special nav colour!**

Below is a single image.
{% include image.html id="example1" images="https://via.placeholder.com/1920x1080.png?text=Example+Image+1" %}

Below is a slider of images.
{% include imageslider.html id="exampleSlider" images=page.exampleGallery %}


Below is a gallery of images.
{% include imagegallery.html id="exampleGallery" images=page.exampleGallery %}
