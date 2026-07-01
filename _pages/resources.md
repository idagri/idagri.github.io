---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
redirect_from:
  - /advice/
  - /predoc-tips/
  - /predoc_tips/
---

{% include base_path %}

<style>
.res-card{ border-left:3px solid rgba(33,145,140,.4); padding:.25rem 0 .25rem .8rem; margin:.9rem 0; }
.res-card.has-img{ display:flex; gap:.9rem; align-items:flex-start; }
.res-card.has-img img{ width:140px; height:96px; object-fit:cover; border-radius:6px; flex:0 0 auto; border:1px solid #e4e4e4; }
.res-card .rt{ font-weight:700; font-size:.97rem; margin:0 0 .15rem; }
.res-card .rd{ font-size:.85rem; color:#5f5f5f; line-height:1.5; margin:0; }
.res-card .rd a{ font-weight:600; }
@media (max-width:40em){ .res-card.has-img img{ width:92px; height:68px; } }
html[data-theme="dark"] .res-card .rd{ color:#b5b5b5; }
</style>

Things I share with students and collaborators: how to find a predoc, AI tools for research, useful datasets, and research tools and guides.

## Predoc Tips

<details markdown="1">
<summary>Sources for finding predoctoral and RA positions</summary>

This list is not exhaustive, but it's a good place to start.

**A hub of predoc resources.** [Predoc.org](https://predoc.org/who-we-are) collects useful materials, including practice coding tasks and a newsletter with advertised positions.

**Sites that aggregate many postings**

- NBER posts non-NBER RA positions [here](https://conference.nber.org/jobs/nonnberjobs.html), and advertises some directly [here](https://www.nber.org/career-resources/calls-fellowship-applications).
- Professors and others tag relevant RA postings on the [@econ_RA Twitter/X page](https://twitter.com/econ_ra) (no account needed to read).

**Organized predoc programs with a set hiring cycle**

- Stanford: [SIEPR predoctoral research fellows program](https://siepr.stanford.edu/programs/siepr-predoctoral-research-fellows-program)
- Chicago: EPIC (Energy Policy Institute)
- Harvard: EPoD Research Fellow postings [here](https://epod.cid.harvard.edu/jobs-opportunities)
- Harvard: Opportunity Insights (two-year commitment) [here](https://opportunityinsights.org/joinourteam/)
- Yale: [predoctoral fellows program](https://tobin.yale.edu/tobin-predoctoral-fellows)
- Princeton: a [cross-department university program](https://graddiversity.princeton.edu/pre-doctoral-fellowship-initiative)

**Programs for US citizens and/or permanent residents only**

- [Harvard Research Scholar Initiative](https://gsas.harvard.edu/diversity/research-scholar-initiative) (no visa sponsorship)
- [PhD Excellence Initiative](https://www.phdexcellence.org/apply/) (NYU Stern)

**Other sources to check**

- [J-PAL Careers](https://www.povertyactionlab.org/careers) (note: some J-PAL roles do not sponsor visas, but other postings do)
- [Innovations for Poverty Action (IPA)](https://www.poverty-action.org/work-with-ipa/current-opportunities)
- Brown and Princeton often post in their own career portals, e.g. [Predoctoral Research Jobs at Princeton](https://research-princeton.icims.com/jobs/search)
- The [World Bank](https://worldbankgroup.csod.com/ats/careersite); look for Research Assistant and ET Consultant roles

**Guides**

- [J-PAL's 2-page guide](https://www.dropbox.com/s/yp6g51o9rt0ghr7/JPAL-RAship-guide-Advice-for-Landing-an-RA-ship.pdf) on landing an RA position
- My [archived predoc search guide](https://www.dropbox.com/s/qc3wrgwhimpa8tv/Pre-Doc-search-guide-202011.pdf) (PDF, Nov 2020)

</details>

## AI Tools

I ran a hands-on workshop for economists at UCSD on **Claude Cowork + Code**: a chat-based AI assistant that reads your LaTeX drafts, writes and runs Stata/R/Python, and works directly with your project files, no terminal required.

<div class="res-card">
<p class="rt">Claude Cowork for economists: workshop</p>
<p class="rd"><a href="/files/ai-cowork-workshop-slides.pdf">Workshop slides (PDF)</a> · <a href="https://x.com/_IdaGri/status/2056430027739107609">workshop thread on X</a></p>
</div>

## Data

Curated datasets I point students to.

<details markdown="1">
<summary><b>Geospatial data</b> for development &amp; urban research</summary>

For a broad catalog of global and US spatial data, the [UPenn Libraries GIS guide](https://guides.library.upenn.edu/c.php?g=1321452&p=9876288) is a great starting point. The sources I reach for most:

- **[GHS - Global Human Settlement Layer](https://human-settlement.emergency.copernicus.eu/)** (JRC / Copernicus). Global gridded built-up surface (GHS-BUILT), population (GHS-POP), and a settlement / degree-of-urbanization layer (GHS-SMOD), plus the Urban Centre Database (GHS-UCDB) of consistently delineated cities. I mostly use the GHS-POP population grids (1975-2020) and the Urban Centre Database to define and track cities over time.
- **[DHS - Demographic and Health Surveys](https://dhsprogram.com/)**. Household survey microdata across many developing countries. The geospatial program adds (randomly displaced) GPS cluster coordinates and spatial covariates such as night lights, so health and wellbeing outcomes can be tied to place; the confidential GPS data needs a short access request.
- **Night lights.** VIIRS and DMSP nighttime-lights rasters, a standard proxy for local economic activity (Matt Lowe's night-lights and ArcGIS guide is a good hands-on introduction).
- **[GADM](https://gadm.org/)**. My default source for administrative boundaries (country down to level 2-3) when I need clean, current admin polygons.
- **[IPUMS International](https://international.ipums.org/international/geography_gis.shtml)**. Harmonized (consistent-over-time GEOLEV1 / GEOLEV2) and unharmonized (year-specific) administrative boundaries that link directly to census microdata; see the [GIS boundary files](https://international.ipums.org/international/gis.shtml). For the US, [IPUMS USA](https://usa.ipums.org/usa/) does the same with US census data.
- **[geo4.dev data catalog](https://www.geo4.dev/library?cat=Data+Catalog)**. A catalog of spatial datasets aimed specifically at development research.

</details>

<details markdown="1">
<summary><b>Mental health &amp; education data</b></summary>

Datasets for research on student mental health, wellbeing, and education. *(In progress, more soon.)*

</details>

## Research Tools

<div class="res-card has-img">
<img src="/images/res-stata-map.jpg" alt="A US choropleth map made with Stata's spmap">
<div>
<p class="rt"><a href="https://github.com/idagri/stata-tools">Stata tools and guides</a></p>
<p class="rd">Useful Stata tools with self-help guides, including making maps (SPMAP / GRMAP) and sample do-files.</p>
</div>
</div>

<div class="res-card has-img">
<img src="/images/res-mapdigit.jpg" alt="A historical map being digitized">
<div>
<p class="rt"><a href="https://github.com/Xu-Haicheng/Digitizing-Historical-Maps-With-QGIS-and-Python/blob/main/Digitizing_Historical_Maps_Guide.ipynb">Digitizing historical maps with QGIS and Python</a></p>
<p class="rd">A step-by-step guide to georeferencing and digitizing historical maps (co-authored with a lab student).</p>
</div>
</div>

<div class="res-card has-img">
<img src="/images/res-shrug.jpg" alt="Map of India showing distance to the nearest urban area">
<div>
<p class="rt"><a href="https://www.devdatalab.org/shrug">SHRUG: open geospatial data for India</a></p>
<p class="rd">The Socioeconomic High-resolution Rural-Urban Geographic Platform: open data covering roughly 600,000 villages and 8,000 towns in India, from the Development Data Lab.</p>
</div>
</div>

More of my code, maps, and guides are on my [GitHub profile](https://github.com/idagri).
