---
permalink: /
title: ""
excerpt: "Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an associate research scientist at [DisneyResearch\|Studios](https://studios.disneyresearch.com/) in Zürich and my research interests are in computer vision, computer graphics and machine learning. I did my PhD at [Technicolor R&I](http://www.technicolor.com/en/innovation/research-innovation/ri-laboratories) Rennes jointly with [Morpheo](http://morpheo.inrialpes.fr/) team at INRIA Grenoble. Before joining Disney, I was a postdoctoral researcher in the [GraphDeco](https://team.inria.fr/graphdeco/) group at INRIA Sophia-Antipolis.

Publications
------
<style style="text/css">
  	.hoverTable{
		width:85%; 
		border-collapse:collapse; 
		border: 0px;
	}
	.hoverTable td{ 
		padding:7px; border:#4e95f4 0px solid;
	}
	/* Define the default color for all the table rows */
	.hoverTable tr{
		background: #ffffff;
	}
	/* Define the hover highlight color for the table row */
    .hoverTable tr:hover {
          background-color: #f7f7f7;
    }
</style>

<table class="hoverTable">
  <col style="width:75%">
  <col style="width:25%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>


