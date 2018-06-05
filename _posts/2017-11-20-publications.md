---
layout: page
title: "Publications"
category: ref
date: 2017-11-20 15:24:20
order: 1
---

This page lists all publications that were created during the course of the PhD thesis.
For a full list of my publications, check <a href="https://thdiaman.github.io/publications">here</a>.

### Journal Articles
{% assign journals = site.ref | where: "type" , "journal" | sort: 'date' | reverse %}
{% for pub in journals %}
  {% include publication.html %}
{% endfor %}

### Book Chapters
{% assign bookchapters = site.ref | where: "type" , "bookchapter" | sort: 'date' | reverse %}
{% for pub in bookchapters %}
  {% include publication.html %}
{% endfor %}

### Conference Papers
{% assign conferences = site.ref | where: "type" , "conference" | sort: 'date' | reverse %}
{% for pub in conferences %}
  {% include publication.html %}
{% endfor %}

