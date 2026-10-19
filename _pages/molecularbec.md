---
title: "Molecular BEC"
layout: textlay
excerpt: "Molecular BEC"
sitemap: false
permalink: /molecularbec
---

# Molecular BEC

We are building a new apparatus to produce NaCs molecular Bose-Einstein condensates. Our aim is to load the molecules into optical lattices and then use quantum gas microscopy to study the rich quantum many-body physics that emerges due to the interplay of tunneling and long-range interactions.

More details are coming soon, but in the meantime, here are some pictures of the apparatus and the team at work in the lab.

<style>
#carousel {
    width: 70%;
    margin: 0 auto;
}

#carousel .item img {
    width: 100%;
    height: auto;
}
</style>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="8000" data-pause="hover">

    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">

        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/nacspic/Chris_CsAOM1.jpeg"
                 alt="Cs AOM System" />
            <div class="carousel-caption mb-4 text-light">
                <p>Chris (PhD) aligning part of the laser system that will be used to laser cool Caesium atoms.</p>
            </div>
        </div>

        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/nacspic/Niamh_NaLocking1.jpeg"
                 alt="Locking the vexlum." />
            <div class="carousel-caption bg-dark mb-4 text-light">
                <p>Niamh (PhD) testing a frequency modulation spectroscopy (FMS) setup for our Sodium laser.</p>
            </div>
        </div>

    </div>

    <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>

    <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>

</div>

## Team Members

Please see [Join us!]({{ site.url }}{{ site.baseurl }}/join-us) for current openings or contact [Prof. Simon L. Cornish](mailto:s.l.cornish@durham.ac.uk).
## Lab Publications

Coming soon!

## Collaborations

We are part of the QSMol consortium. The aim of this project is to explore the emergent phenomena that arises when using ultracold polar molecules as a platform for simulating strongly-correlated quantum systems.

Link to website: [https://www.qsmol.uk/](https://www.qsmol.uk/)

<!-- ### Lab publications
#### Papers
{% assign molecularbec_papers = site.data.publist | where:"lab", "molecularbec" %}
{% assign paper_counter = molecularbec_papers.size %}

{% for publi in molecularbec_papers %}

  \[{{ paper_counter }}\] {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

  {% assign paper_counter = paper_counter | minus:1 %}

{% endfor %}

<p> &nbsp; </p>
#### PhD theses
{% assign combined_members = site.data.team_members | concat: site.data.alumni %}
{% assign molecularbec_theses = combined_members | where:"thesis_lab", "molecularbec" %}
{% assign thesis_by_year = molecularbec_theses | sort: "thesis_year" | reverse %}

{% for publi in thesis_by_year %}
  {% if publi.thesis_link %}
  {{publi.name}}: [_{{publi.thesis_title}}_ ({{publi.thesis_year}})]({{publi.thesis_link}})
  {% endif %}
{% endfor %} -->
