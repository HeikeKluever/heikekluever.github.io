---
layout: page
permalink: /publications/
title: publications
description: Below you can find a list of peer-reviewed articles I have (co-)​authored. There is also a list of books I have (co-)​authored or (co-)​edited.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>articles</h2>

{% bibliography -f publications -q @article %}

<h2 style="margin-top: 80px;">books</h2>

{% bibliography -f publications -q @book %}

</div>
