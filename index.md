---
layout: splash
title: "नमस्ते — I'm Sandeep"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/img/cover.jpg
  actions:
    - label: "Read the Blog"
      url: /blog/
    - label: "Download CV"
      url: /assets/files/CV-Sandeep.pdf   # ✅ ensure correct path
excerpt: "PhD Research Scholar at IIT (ISM) Dhanbad. I write about deep learning for finance, crypto policy, and reproducible research."
feature_row:
  - image_path: /assets/img/feature-research.jpg
    alt: "Research"
    title: "Research"
    excerpt: "Investor Sentiment, Crypto Adoption, Portfolio Optimization."
    url: "/research/"   # ✅ cleaner permalink
    btn_label: "Explore"
    btn_class: "btn--primary"
  - image_path: /assets/img/feature-blog.jpg
    alt: "Blog"
    title: "Blog"
    excerpt: "Posts with code, visuals, and practical takeaways."
    url: "/blog/"
    btn_label: "Read"
    btn_class: "btn--primary"
  - image_path: /assets/img/feature-teaching.jpg
    alt: "Teaching"
    title: "Teaching"
    excerpt: "Workshops, guest lectures, and course materials."
    url: "/teaching/"   # ✅ cleaner permalink
    btn_label: "View"
    btn_class: "btn--primary"
---

{% include feature_row %}
