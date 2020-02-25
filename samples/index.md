---
title: Sample Home
keywords: sample
tags: [sample]
sidebar: mydoc_sidebar
permalink: /samples/index.html
summary: Sample home?
---

# Sample Home

__This is sample home... Sample Home__


## Simple Markup Links 1 (Works)

* [Root](../index.html)
* [Sample Home](index.html)
* [Sample Page A](page-a.html)


## Simple Markup Links 2 (Works)
* [Root](../index.html)
* [Sample Home](./index.html)
* [Sample Page A](./page-a.html)

---

## Complex Markup Links 1 (Works)

* [Root]({{ '/index.html' | relative_url }})
* [Sample Home]({{ '/samples/index.html' | relative_url }})
* [Samples Page A]({{ '/samples/page-a.html' | relative_url }})

_breaks in Atom Markdown Preview_

---

## Complex HTML Links 1 (Works)

* <a href="{{ 'index.html' | relative_url }}">Root</a>
* <a href="{{ 'samples/index.html' | relative_url }}">Sample Home</a>
* <a href="{{ 'samples/page-a.html' | relative_url }}">Sample Page A</a>

## Complex HTML Links 2 (Works)

* <a href="{{ '/index.html' | relative_url }}">Root</a>
* <a href="{{ '/samples/index.html' | relative_url }}">Sample Home</a>
* <a href="{{ '/samples/page-a.html' | relative_url }}">Sample Page A</a>

---


In _config.yaml set **baseurl** to be blank

```baseurl:```


---

## Simple Markup Image 1 (Works)

![](../images/nom.jpg)


## Complex Markup Image 2 (Works)

![]({{ 'images/nom.jpg' | relative_url }})

_breaks in Atom Markdown Preview_




---

{% include links.html %}

