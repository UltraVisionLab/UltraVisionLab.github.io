---
title: "UltraVision+ Lab - Publications"
layout: gridlay
excerpt: "UltraVision+ Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

In this page, you can find the our publications in [2025](#2025),  [2024](#2024),  [2023](#2023),  [2022](#2022),  [2021](#2021),  [before 2021](#2021), which can also be found in <a href="https://scholar.google.com.hk/citations?user=fo3rmtwAAAAJ&hl=en" target="_blank">Google Scholar</a>.

<sup>*</sup> indicates equal contribution

<sup>†</sup> indicates corresponding author

## Highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist2024 %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title1 }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong>{{ publi.display }}</strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


<!-- ## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>

## Full List of publications -->

## 2025

{% for publi in site.data.publist2025 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}

## 2024

{% for publi in site.data.publist2024 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}

## 2023

{% for publi in site.data.publist2023 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}

## 2022

{% for publi in site.data.publist2022 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}

## 2021

{% for publi in site.data.publist2021 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}

## Before 2021

{% for publi in site.data.publist2020 %}

  {{ forloop.index }}. {{ publi.title }} <br />
  {{ publi.authors }} <br />
  {{ publi.display }}

{% endfor %}
