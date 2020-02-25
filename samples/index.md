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


## Simple Markup Links 1

* [Root](../index.html)
* [Sample Home](index.html)
* [Sample Page A](page-a.html)


## Simple Markup Links 2
* [Root](../index.html)
* [Sample Home](./index.html)
* [Sample Page A](./page-a.html)


## Simple Markup Links 3 (Don't work)

* [Root](/index.html)
* [Sample Home](/samples/index.html)
* [Sample Page A](/samples/page-a.html)

---


## Complex Markup Links 1

* [Root]({{ '/index.html' | relative_url }})
* [Sample Home]({{ '/samples/index.html' | relative_url }})
* [Samples Page A]({{ '/samples/page-a.html' | relative_url }})


---

## Complex HTML Links 1

* <a href="{{ 'index.html' | relative_url }}">Root</a>
* <a href="{{ 'samples/index.html' | relative_url }}">Sample Home</a>
* <a href="{{ 'samples/page-a.html' | relative_url }}">Sample Page A</a>

## Complex HTML Links 2

* <a href="{{ '/index.html' | relative_url }}">Root</a>
* <a href="{{ '/samples/index.html' | relative_url }}">Sample Home</a>
* <a href="{{ '/samples/page-a.html' | relative_url }}">Sample Page A</a>

---


In _config.yaml set **baseurl** to be blank

```baseurl:```


---


![](../images/nom.jpg)

![]({{ 'images/nom.jpg' | relative_url }})






---

{% include links.html %}

