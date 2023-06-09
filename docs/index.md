---
layout: default
title: Home
nav_exclude: true
---

# Carob Data Pages

The aim of the *Carob project* is to create reproducible workflows that reshape primary agricultural research open data from experiments and surveys into a standard format, and to aggregate individual data sets into larger collections that can be used in further research. We do this by writing an R script for each individual dataset. Feel free to improve these scripts, or provide new ones through a pull request (see below for more info).

## What Can You Find Around Here

This page offers provides information about the project, from the guidelines, to the workflows, and also the data.

- Read how you can contribute to the project and find more data using the [Gardian](https://gardian.bigdata.cgiar.org/) website.
- This page also provides information about how to get your data.
- Check the [FAQs](https://egbendito.github.io/jekyll-theme-rtd/faqs.html) for some quick overview of the Carob.

### Acknowledgments

This work is a community effort aiming to make open primary research data more accessible and re-usable for many purposes. This effort is partly supported by a grant to [CGIAR Excellence in Agronomy initiative](https://www.cgiar.org/initiative/11-excellence-in-agronomy-eia-solutions-for-agricultural-transformation/) and by the University of California, Davis.

#### Thank you to the contributors of Carob!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

