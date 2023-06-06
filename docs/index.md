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

## 🚧 Warning!

This theme is currently a **Work-In-Progress** but, while some things might be
broken, it should be already usable.

Missing features are listed in the GitHub issues with the
[to-do label](https://github.com/carlosperate/jekyll-theme-rtd/issues?q=is%3Aissue+is%3Aopen+label%3Ato-do),
and any known issues are listed with the
[bug label](https://github.com/carlosperate/jekyll-theme-rtd/issues?q=is%3Aissue+is%3Aopen+label%3Abug).

Contributions are very welcomed!

### Acknowledgments

This work is a community effort aiming to make open primary research data more accessible and re-usable for many purposes. This effort is partly supported by a grant to [CGIAR Excellence in Agronomy initiative](https://www.cgiar.org/initiative/11-excellence-in-agronomy-eia-solutions-for-agricultural-transformation/) and by the University of California, Davis.

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

This is a port of the
[Read The Docs](https://sphinx-rtd-theme.readthedocs.io) theme to
[Jekyll](https://jekyllrb.com/), so that it can be used with GitHub Pages.

You are previewing the theme right now, as you navigate
[this documentation](https://carlosperate.github.io/jekyll-theme-rtd):

![screenshot](assets/img/screenshot.png)

The original [Read The Docs](https://readthedocs.org)
[theme]((https://sphinx-rtd-theme.readthedocs.io)) was created for the
[Sphinx](https://www.sphinx-doc.org/) documentation generator, and so it is
designed specifically for docs.

Combined with [GitHub Pages](https://pages.github.com) it's a great and easy
way to document your projects!
