---
layout: archive
title: "Undergraduate–Graduate Research Lab"
permalink: /lab/
author_profile: true
---

{% include base_path %}

<style>
.proj-group{ margin:1.1rem 0 1.5rem; }
.proj-group h3{ border-bottom:2px solid; padding-bottom:.2rem; font-size:1.02rem; margin-bottom:.2rem; }
.proj-group.urban h3{ border-color:#3B528B; }
.proj-group.well  h3{ border-color:#21918C; }
.proj-intro{ font-size:.86rem; color:#5f5f5f; margin:.5rem 0 .2rem; line-height:1.55; }
.proj-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:1rem 1.5rem; margin-top:.8rem; }
.proj{ border-left:3px solid; padding-left:.75rem; }
.proj-group.urban .proj{ border-color:rgba(59,82,139,.35); }
.proj-group.well  .proj{ border-color:rgba(33,145,140,.4); }
.proj-t{ margin:0 0 .15rem; font-weight:700; font-size:.94rem; line-height:1.3; }
.proj-d{ margin:0; font-size:.83rem; color:#5f5f5f; line-height:1.5; }
.proj-d a{ font-weight:600; }
.proj-tools{ color:#6a7480; }
.place{ display:inline-block; font-size:.74rem; font-weight:600; background:rgba(33,145,140,.13); color:#13716b;
  border:1px solid rgba(33,145,140,.3); border-radius:1rem; padding:.14rem .65rem; margin:.18rem .3rem .18rem 0; }
@media (max-width:50em){ .proj-grid{ grid-template-columns:1fr; } }
html[data-theme="dark"] .proj-d,.proj-intro{ color:#b5b5b5; }
html[data-theme="dark"] .proj-group.urban .proj{ border-color:rgba(110,140,210,.4); }
html[data-theme="dark"] .proj-group.well  .proj{ border-color:rgba(45,170,160,.45); }
html[data-theme="dark"] .place{ background:rgba(45,170,160,.2); color:#6fd0c8; border-color:rgba(45,170,160,.4); }
</style>

Since Fall 2023, I have led an **Undergraduate–Graduate Research Lab (URL)** at UC San Diego, mentoring 10–20 undergraduates each quarter on real research projects in development, urban, and education economics. Students work hands-on with Stata, Python, R, and QGIS, and present their work at the end of each quarter.

<figure class="align-center">
  <img src="/images/lab-collage.jpg" alt="Lab meetings, group work, and end-of-quarter presentations">
</figure>

## Sample projects

<div class="proj-group urban" markdown="0">
<h3>GIS lab — spatial data</h3>
<p class="proj-intro">A core thread of the lab is building geospatial datasets from scratch: turning raw satellite imagery and paper maps into analysis-ready spatial data. A multi-quarter effort digitizes and classifies informal settlements (slums) from high-resolution imagery, alongside historical-map digitization and accessibility mapping.</p>
<div class="proj-grid">
<div class="proj">
<p class="proj-t">Mapping &amp; digitizing informal settlements</p>
<p class="proj-d">Building a protocol to detect and delineate slums in high-resolution Planet satellite imagery and convert it into classified, analysis-ready spatial data, pairing manual image labeling with machine-learning classification. <a href="/files/url-gis-slums-classification.pdf">Slides</a> <span class="proj-tools">· India &amp; Indonesia · QGIS · Python</span></p>
</div>
<div class="proj">
<p class="proj-t">Digitizing historical maps</p>
<p class="proj-d">Georeferencing and digitizing historical maps into spatial data. <a href="https://github.com/Xu-Haicheng/Digitizing-Historical-Maps-With-QGIS-and-Python/blob/main/Digitizing_Historical_Maps_Guide.ipynb">QGIS + Python guide</a> <span class="proj-tools">· co-authored with a lab student</span></p>
</div>
<div class="proj">
<p class="proj-t">Travel time and urban accessibility</p>
<p class="proj-d">Mapping travel times to jobs, schools, and services across urban areas. <a href="/files/url-travel-time-qgis.pdf">Slides</a> <span class="proj-tools">· QGIS · spatial data</span></p>
</div>
<div class="proj">
<p class="proj-t">Crime, news, and cities</p>
<p class="proj-d">Scraping Portuguese-language newspaper archives to build a dataset of violence events in Rio's favelas. <a href="/files/url-rio-crime-scraping.pdf">Slides</a> <span class="proj-tools">· Rio de Janeiro · Python</span></p>
</div>
</div>
</div>

<div class="proj-group well" markdown="0">
<h3>Wellbeing, education &amp; talent</h3>
<div class="proj-grid">
<div class="proj">
<p class="proj-t">Finding "missing talent"</p>
<p class="proj-d">Using national exam data (such as Brazil's ENEM) and new assessments to identify high-potential students. <a href="/files/url-hidden-talent-enem.pdf">Slides</a> <span class="proj-tools">· Central America &amp; Brazil</span></p>
</div>
<div class="proj">
<p class="proj-t">The economics of sleep</p>
<p class="proj-d">Comparing self-reported and wristband-measured sleep in two field experiments to see who benefits most from sleep interventions. <span class="proj-tools">India &amp; United States · Stata, R</span></p>
</div>
<div class="proj">
<p class="proj-t">Education and migration</p>
<p class="proj-d">Reviewing and synthesizing the literature linking migration, schooling, and student outcomes. <a href="/files/url-education-migration.pdf">Slides</a></p>
</div>
<div class="proj">
<p class="proj-t">Compulsory schooling laws across countries</p>
<p class="proj-d">A multi-country dataset compiling compulsory-schooling-law reforms (top-25 countries plus Latin America): policy timing, affected cohorts, and sources, to study effects on schooling. <a href="/files/url-csl-schooling-laws.pdf">Review slides</a> <span class="proj-tools">· Stata</span></p>
</div>
<div class="proj">
<p class="proj-t">Gender in economics PhD placements</p>
<p class="proj-d">A semi-automated scraper of PhD job-market placements across economics, business, and public policy, with gender and academic/industry classifiers, feeding an analysis of gender composition and outcomes. <a href="https://jclluo.github.io/ECON_PHD_Gender_Inequality_Analysis/analysis.html">Student analysis site</a> · <a href="https://github.com/schan676/Gender_composition_STEM">data repo</a> · <a href="/files/url-econ-phd-gender-gap.pdf">slides</a> <span class="proj-tools">· Python</span></p>
</div>
</div>
</div>

The students I have worked with, in the lab and beyond, are pursuing further education at the University of Michigan, Tufts, and Oxford, and have obtained predoctoral fellowships and RA positions at the Federal Reserve, Stanford, and elsewhere.

## Interested in joining?

UCSD undergraduates curious about empirical research in development, urban, or education economics are welcome to reach out at [idagri@ucsd.edu](mailto:idagri@ucsd.edu).
