---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://iiif-prod.nypl.org/index.php?id=62071&t=v" %}

{% include feature/nav-menu.html sections="About the Collection;Data Collection;Individual Works;Project Information;Site Information" %}

## About the Collection
This collection represents student theses and dissertations on Indigenous people and subjects, collected from Open Access Institutional Repositories in the Pacific Northwest states of Washington and Oregon. The goal of the collection is to promote the accessibility and visibility of Indigenous scholarship and data. 


### Data Collection
**Institutional Repositories**

The universities represented here were chosen by first compiling a list of research institutions in Washington and Oregon that had digital institutional repositories with open access content. After a preliminary exploration of the repositories to estimate how many relevant works each contained, I prioritized data collection from universities with high (50+) amounts of relevant works.


<iframe title="Number of Works by University" aria-label="Pie Chart" id="datawrapper-chart-xpNTB" src="https://datawrapper.dwcdn.net/xpNTB/6/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}}))}();
</script>


**Individual Works**

Indigneous work is often interdisciplinary, and often comes from scholars outside of Indigenous/Native American programs. Works were selected for inclusion based on literary warrant, or how the works self-identified: through keywords in the title, abstract, content, or subject tags. Author disclosure of Indigenous identity was not a collection requirement. Only student theses, dissertations, and field projects were chosen, due to the prevalence of these works within institutional repositories and for curation in the DTL's OCLC collections.

<div style="min-height:400px" id="datawrapper-vis-a84Dh"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/a84Dh/embed.js" charset="utf-8" data-target="#datawrapper-vis-a84Dh"></script><noscript><img src="https://datawrapper.dwcdn.net/a84Dh/full.png" alt="" /></noscript></div>


The metadata collected for each work was informed by the [Dublin Core Metadata Schema.](https://www.dublincore.org/about/) The fields include: objectid, title, creator, date, work type, discipline, subject, description, institution, location, description, filename, format, OCLC number, and record type. Metadata was hand-collected by myself (Avery Johnson) along with assistance from several DTL interns.


**Project Information**

This digital collection was curated by Avery Johnson, graduate student at the University of Washington, as part of a Capstone project for the Library and Information Science program. As a white woman, I acknowledge that my understanding of these issues is limited by my privilege and lived experiences, and I am constantly striving to decolonize my practice and perspectives.

This project was sponsored by the [Open Access Digital Theological Library,](https://libguides.thedtl.org/oadtl/about) whose mission "is to curate high-quality content in religious studies and related disciplines from publisher websites, institutional repositories, scholarly societies, archives, and stable public domain collections." The vast majority of works included in this digital collection are cataloged in [OCLC,](https://www.oclc.org/en/worldcat.html) one of the largest integrated library systems in the world, and included in the DTL's OCLC collections.


![Postcard of Tahoma/Mount Rainier and Lake Washington, Seattle](https://iiif-prod.nypl.org/index.php?id=68896&t=g) 
[Image Source:](https://digitalcollections.nypl.org/items/510d47d9-a0b0-a3d9-e040-e00a18064a99) The Miriam and Ira D. Wallach Division of Art, Prints and Photographs: Photography Collection, The New York Public Library. "Mt. Rainier, Lake Washington, Seattle, Wash." New York Public Library Digital Collections. Accessed March 17, 2025. https://digitalcollections.nypl.org/items/510d47d9-a0b0-a3d9-e040-e00a18064a99



### Site Information
The images used on the Home page and the About page are postcards of Tahoma (Washington's Mount Rainier) from the [New York Public Library's digital collection.](https://digitalcollections.nypl.org/)

- [Home Page Image](https://digitalcollections.nypl.org/items/510d47d9-9a77-a3d9-e040-e00a18064a99)
- [About Page Image](https://digitalcollections.nypl.org/items/510d47d9-9b63-a3d9-e040-e00a18064a99) 

Visualizations were created using Rstudio and [Datawrapper](https://www.datawrapper.de/).
