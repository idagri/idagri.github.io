---
layout: archive
title: "Undergraduate-Graduate Research Lab"
permalink: /lab/
author_profile: true
---

{% include base_path %}

<style>
/* one hue (viridis teal), three shades: section (h2, global) > subsection (h3) > project card */
.proj-group{ margin:1.4rem 0 1.7rem; }
.proj-group h3{ border-bottom:2px solid rgba(33,145,140,.55); padding-bottom:.2rem; font-size:1.02rem;
  margin-bottom:.2rem; color:#13716b; }
.proj-intro{ font-size:.86rem; color:#585858; margin:.5rem 0 .2rem; line-height:1.55; }
.proj-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:1rem 1.3rem; margin-top:.85rem; }
.proj{ display:flex; gap:.75rem; align-items:flex-start; border-left:3px solid rgba(33,145,140,.4);
  background:rgba(33,145,140,.05); border-radius:0 8px 8px 0; padding:.6rem .8rem; }
.proj-thumb{ flex:0 0 auto; width:90px; height:64px; border-radius:6px; object-fit:cover;
  box-shadow:0 1px 3px rgba(0,0,0,.14); background:rgba(33,145,140,.12); }
.proj-body{ flex:1 1 auto; min-width:0; }
.proj-t{ margin:0 0 .15rem; font-weight:700; font-size:.94rem; line-height:1.3; color:#1d1d1d; }
.proj-d{ margin:0; font-size:.83rem; color:#585858; line-height:1.5; }
.proj-d a{ font-weight:600; }
.proj-tools{ color:#6a7480; }
.proj.adv{ background:rgba(33,145,140,.11); border-left-color:#21918c; box-shadow:0 1px 5px rgba(33,145,140,.16); }
.adv-badge{ display:inline-block; font-size:.56rem; font-weight:700; text-transform:uppercase; letter-spacing:.04em;
  color:#fff; background:#21918c; border-radius:1rem; padding:.04rem .5rem; margin-left:.4rem; vertical-align:middle; }
.proj-wip{ font-style:italic; color:#6a7480; }
html[data-theme="dark"] .proj.adv{ background:rgba(45,170,160,.14); border-left-color:#2daaa0; }
html[data-theme="dark"] .adv-badge{ background:#2daaa0; color:#0d1520; }
.place{ display:inline-block; font-size:.74rem; font-weight:600; background:rgba(33,145,140,.13); color:#13716b;
  border:1px solid rgba(33,145,140,.3); border-radius:1rem; padding:.14rem .65rem; margin:.18rem .3rem .18rem 0; }
@media (max-width:50em){ .proj-grid{ grid-template-columns:1fr; } }
html[data-theme="dark"] .proj-group h3{ color:#6fd0c8; border-color:rgba(45,170,160,.5); }
html[data-theme="dark"] .proj-t{ color:#e6e9ec; }
html[data-theme="dark"] .proj-d, html[data-theme="dark"] .proj-intro{ color:#b5b5b5; }
html[data-theme="dark"] .proj{ background:rgba(45,170,160,.08); border-color:rgba(45,170,160,.4); }
html[data-theme="dark"] .place{ background:rgba(45,170,160,.2); color:#6fd0c8; border-color:rgba(45,170,160,.4); }
</style>

I've led an **Undergraduate-Graduate Research Lab (URL)** at UC San Diego since Fall 2023, and it's one of my favorite parts of the job. Each quarter I work with 10-20 undergraduates on real research in development, urban, and education economics, split across two labs: a GIS lab for spatial and satellite data, and a Stata-Python lab for the empirical projects. Everyone works hands-on with Stata, Python, R, and QGIS and presents at the end of the quarter.

## Students' Sample Projects

<div class="proj-group" markdown="0">
<h3>GIS lab: spatial data</h3>
<p class="proj-intro">In the GIS lab, we build spatial data from scratch: taking raw satellite images and old paper maps and turning them into something we can actually analyze. Right now that means finding and outlining informal settlements in satellite imagery, digitizing historical maps, and measuring how long it takes people to reach jobs, schools, and services.</p>
<div class="proj-grid">
<div class="proj adv">
<img loading="lazy" class="proj-thumb" src="/images/proj-slums.jpg" alt="Satellite imagery classified into informal, formal, and mixed settlement areas">
<div class="proj-body">
<p class="proj-t">Slum Mapping <span class="adv-badge">Advanced</span></p>
<p class="proj-d">Building a protocol to detect and delineate slums in high-resolution Planet satellite imagery and convert it into classified, analysis-ready spatial data, pairing manual image labeling with machine-learning classification. <a href="/files/url-gis-slums-classification.pdf">Slides</a> <span class="proj-tools">· India &amp; Indonesia · QGIS · Python · <span class="proj-wip">ongoing</span></span></p>
</div>
</div>
<div class="proj adv">
<img loading="lazy" class="proj-thumb" src="/images/proj-histmap.jpg" alt="A historical map georeferenced and digitized into vector spatial data">
<div class="proj-body">
<p class="proj-t">Digitizing historical maps <span class="adv-badge">Advanced</span></p>
<p class="proj-d">Georeferencing and digitizing historical maps into spatial data. <a href="https://github.com/Xu-Haicheng/Digitizing-Historical-Maps-With-QGIS-and-Python/blob/main/Digitizing_Historical_Maps_Guide.ipynb">QGIS + Python guide</a> <span class="proj-tools">· co-authored with a lab student</span></p>
</div>
</div>
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-travel.jpg" alt="A travel-time surface mapping access to jobs, schools, and services">
<div class="proj-body">
<p class="proj-t">Travel time and urban accessibility</p>
<p class="proj-d">Mapping travel times to jobs, schools, and services across urban areas. <a href="/files/url-travel-time-qgis.pdf">Slides</a> <span class="proj-tools">· QGIS · spatial data</span></p>
</div>
</div>
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-rio.jpg" alt="Crime and cities project">
<div class="proj-body">
<p class="proj-t">Crime, news, and cities</p>
<p class="proj-d">Scraping Portuguese-language newspaper archives to build a dataset of violence events in Rio's favelas. <a href="/files/url-rio-scraping-2025.pdf">Slides</a> · <a href="/files/url-rio-crime-scraping.pdf">earlier slides</a> <span class="proj-tools">· Rio de Janeiro · Python</span></p>
</div>
</div>
</div>
</div>

<div class="proj-group" markdown="0">
<h3>Stata-Python lab: wellbeing, education &amp; talent</h3>
<div class="proj-grid">
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-talent.jpg" alt="Distribution of exam scores used to identify high-potential students">
<div class="proj-body">
<p class="proj-t">Finding "missing talent"</p>
<p class="proj-d">Using national exam data (such as Brazil's ENEM) and new assessments to identify high-potential students. <a href="/files/url-hidden-talent-enem.pdf">Slides</a> <span class="proj-tools">· Central America &amp; Brazil</span></p>
</div>
</div>
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-sleep.jpg" alt="Economics of sleep project">
<div class="proj-body">
<p class="proj-t">The economics of sleep</p>
<p class="proj-d">Comparing self-reported and wristband-measured sleep in two field experiments to see who benefits most from sleep interventions. <a href="/files/url-sleep-2026.pdf">Slides</a> <span class="proj-tools">· India &amp; United States · Stata, R</span></p>
</div>
</div>
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-edmig.jpg" alt="Education and migration literature review">
<div class="proj-body">
<p class="proj-t">Education and migration</p>
<p class="proj-d">Reviewing and synthesizing the literature linking migration, schooling, and student outcomes. <a href="/files/url-education-migration.pdf">Slides</a></p>
</div>
</div>
<div class="proj">
<img loading="lazy" class="proj-thumb" src="/images/proj-csl.jpg" alt="Charts of compulsory-schooling-law reforms across countries">
<div class="proj-body">
<p class="proj-t">Compulsory schooling laws across countries</p>
<p class="proj-d">A multi-country dataset compiling compulsory-schooling-law reforms (top-25 countries plus Latin America): policy timing, affected cohorts, and sources, to study effects on schooling. <a href="/files/url-csl-schooling-laws.pdf">Review slides</a> <span class="proj-tools">· Stata</span></p>
</div>
</div>
<div class="proj adv">
<img loading="lazy" class="proj-thumb" src="/images/proj-gender.jpg" alt="Analysis of gender composition in economics PhD job-market placements">
<div class="proj-body">
<p class="proj-t">Gender in economics PhD placements <span class="adv-badge">Advanced</span></p>
<p class="proj-d">A semi-automated scraper of PhD job-market placements across economics, business, and public policy, with gender and academic/industry classifiers, feeding an analysis of gender composition and outcomes. <a href="https://jclluo.github.io/ECON_PHD_Gender_Inequality_Analysis/analysis.html">Student analysis site</a> · <a href="https://github.com/schan676/Gender_composition_STEM">data repo</a> · <a href="/files/url-econ-phd-gender-gap.pdf">slides</a> <span class="proj-tools">· Python</span></p>
</div>
</div>
</div>
</div>

## Outcomes

The students I have worked with at UCSD and beyond have gone on to pursue further education at the University of Michigan, Tufts, and Oxford, and/or have obtained predoctoral fellowships and RA positions at the Federal Reserve, Stanford, and Harvard, among others.

<figure class="align-center">
  <img loading="lazy" src="/images/lab-collage.jpg" alt="Lab meetings, group work, and end-of-quarter presentations">
</figure>
