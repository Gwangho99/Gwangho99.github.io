---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% assign cv_version = site.time | date: "%s" %}

<a href="{{ '/files/cv.pdf' | relative_url }}?v={{ cv_version }}">Download CV (PDF)</a>

<iframe src="{{ '/files/cv.pdf' | relative_url }}?v={{ cv_version }}" width="100%" height="900px" style="border: none;"></iframe>
