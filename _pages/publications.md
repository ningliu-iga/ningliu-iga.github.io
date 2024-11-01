---
layout: page
permalink: /publications/
title: publications
description: selected publications in reversed chronological order. Please refer to <a href='https://scholar.google.com/citations?hl=en&user=EHJLH40AAAAJ&view_op=list_works&sortby=pubdate'>my Google Scholar profile</a> for a full list.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
