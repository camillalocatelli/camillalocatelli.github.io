---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">
<div class="publications">

<h2>Journal Articles</h2>

{% bibliography --query @*[keywords=journal] %}

<h2>Research &amp; Discussion Papers</h2>

{% bibliography --query @*[keywords ^= report] %}

<h2>Working Manuscripts</h2>

{% bibliography --query @*[keywords ^= working] %}

<h2>Newspaper Articles &amp; Blog Posts</h2>

{% bibliography --query @*[keywords ^= blog] %}

</div>
