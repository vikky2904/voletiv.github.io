---
title: Vikram Voleti's publications
layout: default
excerpt: Vikram Voleti's publications
permalink: /publications/
---

## Journal papers

{% for publication in site.data.journal_papers %}

{% include publications.html %}

{% endfor %}

<p>&nbsp;</p>

{% assign numOfJournals = loopindex %}

## Conference papers

{% for publication in site.data.conference_papers %}

{% include publications.html %}

{% endfor %}

<p>&nbsp;</p>

## Thesis / Reports

{% for publication in site.data.reports %}

{% include publications.html %}

{% endfor %}
