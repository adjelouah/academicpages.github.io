---
permalink: /
title: ""
excerpt: "Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an associate research scientist at [Disney Research](https://www.disneyresearch.com/) in Zürich. Before joining Disney, I was a postdoctoral researcher at INRIA in [GraphDeco](https://team.inria.fr/graphdeco/) group working on image and video based rendering in collaboration with George Drettakis. I did my PhD at [Technicolor R&I](http://www.technicolor.com/en/innovation/research-innovation/ri-laboratories) Rennes jointly with [Morpheo](http://morpheo.inrialpes.fr/) team at INRIA Rhône-Alpes Grenoble, under the supervision of Edmond Boyer and Patrick Perez.


Publications
------
<style style="text/css">
  	.hoverTable{
		width:80%; 
		border-collapse:collapse; 
	}
	.hoverTable td{ 
		padding:7px; border:#4e95f4 1px solid;
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
  <col style="width:70%">
  <col style="width:30%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>


