---
layout: default
title: The Title of the Page!
date: 2019-01-28T23:24:41-04:00
header:
  overlay_color: "#00000000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/home_road_ahead.jpg
excerpt: This is the executive summary. It will be used in archive and listing pages.
intro:
  - excerpt: This is the intro blurb. Please select from the below choices.
feature_row:
  - image_path: /assets/images/teaser_300x200.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/teaser_300x200.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/teaser_300x200.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---
<section class="site-description">
{{ site.description }}
</section>

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
