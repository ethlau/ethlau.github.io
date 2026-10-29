---
layout: page
permalink: /publications/
title: publications
description: 62 refereed journal papers, of which 14 first-author and 8 student-led. Citations 4694, h-index 35 (Google Scholar, October 2026).
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Refereed journal papers</h2>
{% bibliography --query @article %}

<h2 class="bibliography">Submitted and in preparation</h2>
{% bibliography --query @unpublished %}

<h2 class="bibliography">Other publications</h2>
{% bibliography --query @misc %}

</div>

A PDF version of this list is included in my [CV]({{ '/files/CV.pdf' | relative_url }}). See also my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=Uzv1f1oAAAAJ).
