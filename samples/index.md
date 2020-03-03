---
title: Samples Home
keywords: sample
tags: [sample]
sidebar: mydoc_sidebar
permalink: /samples/
summary: Sample directory test...
---

# Samples Home

Testing a directory structure with files in it...


## Simple Markup Links 1 (Works)

* [Root](../index.html)
* [Samples Home](index.html)
* [Samples Page A](page-a.html)


## Simple Markup Links 2 (Works)
* [Root](../index.html)
* [Samples Home](./index.html)
* [Samples Page A](./page-a.html)

---

## Complex Markup Links 1 (Works)

* [Root]({{ '/index.html' | relative_url }})
* [Samples Home]({{ '/samples/index.html' | relative_url }})
* [Samples Page A]({{ '/samples/page-a.html' | relative_url }})

_breaks in Atom Markdown Preview and GitHub repository_

---

## Complex HTML Links 1 (Works)

* <a href="{{ 'index.html' | relative_url }}">Root</a>
* <a href="{{ 'samples/index.html' | relative_url }}">Samples Home</a>
* <a href="{{ 'samples/page-a.html' | relative_url }}">Samples Page A</a>

## Complex HTML Links 2 (Works)

* <a href="{{ '/index.html' | relative_url }}">Root</a>
* <a href="{{ '/samples/index.html' | relative_url }}">Samples Home</a>
* <a href="{{ '/samples/page-a.html' | relative_url }}">Samples Page A</a>

---


In _config.yaml set **baseurl** to be blank

```baseurl:```


---

## Simple Markup Image 1 (Works)

![](../images/nom.jpg)


## Complex Markup Image 2 (Works)

![]({{ 'images/nom.jpg' | relative_url }})

_breaks in Atom Markdown Preview and GitHub repository_




---

{% include links.html %}

