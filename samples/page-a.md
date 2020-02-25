---
title: Sample Page A
keywords: sample
tags: [sample]
sidebar: mydoc_sidebar
permalink: /samples/page-a.html
summary: Sample Page A
---

# Page A


## Simple Markup Links

* [Root](../index.html)
* [Sample Home](index.html)
* [Sample Page A](page-a.html)
* [Sample Page B](page-b.html)


## Complex HTML Links

* <a href="{{ 'index.html' | relative_url }}">Root</a>
* <a href="{{ 'samples/index.html' | relative_url }}">Sample Home</a>
* <a href="{{ 'samples/page-a.html' | relative_url }}">Sample Page A</a>
* <a href="{{ 'samples/page-b.html' | relative_url }}">Sample Page B</a>


---

{% include links.html %}



