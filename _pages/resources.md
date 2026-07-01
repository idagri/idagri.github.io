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
.ds-youth{ display:inline-block; font-size:.6rem; font-weight:700; text-transform:uppercase; letter-spacing:.03em;
  color:#13716b; background:rgba(33,145,140,.13); border:1px solid rgba(33,145,140,.32); border-radius:1rem;
  padding:.02rem .45rem; vertical-align:middle; white-space:nowrap; }
@media (max-width:40em){ .res-card.has-img img{ width:92px; height:68px; } }
html[data-theme="dark"] .res-card .rd{ color:#b5b5b5; }
html[data-theme="dark"] .ds-youth{ color:#6fd0c8; background:rgba(45,170,160,.18); border-color:rgba(45,170,160,.4); }
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
<summary><b>Mental health &amp; wellbeing data</b></summary>

Publicly available datasets that carry a validated mental-health or wellbeing measure. Most are free with registration; restricted or paid ones are flagged. I note the instrument (CES-D, PHQ-9, K6, diagnostic interview, etc.) where it matters, and a <span class="ds-youth">youth</span> tag marks datasets whose sample includes adolescents or young adults, so they can be used to study student / youth mental health.

**Development and low- or middle-income country panels**

- **[IFLS - Indonesia Family Life Survey](https://www.rand.org/health/surveys/FLS/IFLS/access.html)** (RAND). CES-D-10 depression and a life-satisfaction module in the 2007 and 2014 waves (age 15+); 13 provinces, ~83% of the population, 5 waves 1993-2015. Free with registration. <span class="ds-youth">youth</span>
- **[MxFLS - Mexican Family Life Survey](https://www.ennvih-mxfls.org/english/)** (ENNViH). A Zung-derived depression and anxiety scale (Calderon) in all three waves (2002, 2005-06, 2009-12), age 15+; nationally representative, ~35,000 people. Free with registration. <span class="ds-youth">youth</span>
- **[Young Lives](https://www.younglives.org.uk/)** (Oxford; data via UK Data Service, SN 8678). Child-to-young-adult cohorts in Ethiopia, India, Peru, and Vietnam, with caregiver SRQ-20, Cantril life-satisfaction, psychosocial and self-concept scales, and GAD-7 + PHQ-8 in the young-adult rounds (2020, 2023-24); 7 rounds since 2002. Free with registration. <span class="ds-youth">youth</span>
- **[NIDS - National Income Dynamics Study](https://www.datafirst.uct.ac.za/dataportal/index.php/collections/NIDS)** (South Africa, SALDRU). CES-D-10 depression in all 5 waves (2008-2017), age 15+ (the COVID-era NIDS-CRAM uses PHQ-2). Free with registration. <span class="ds-youth">youth</span>
- **[CFPS - China Family Panel Studies](https://opendata.pku.edu.cn/dataverse/CFPS)** (Peking University). CES-D depression (20-item through 2012, 8-item from 2016) and Kessler K6 in early waves; adolescents self-report from age 10; 25 provinces, biennial since 2010. Free with registration and a data-use agreement. <span class="ds-youth">youth</span>

**Cross-national**

- **[WHO World Mental Health Surveys](https://www.hcp.med.harvard.edu/wmh/)** (Harvard). The gold standard: full CIDI diagnostic interviews (DSM/ICD depression, anxiety, substance disorders) across 30+ countries; mostly adults. Access is restricted (consortium data-use agreement); a separate college-student sub-study exists.
- **[Global Burden of Disease](https://vizhub.healthdata.org/gbd-results/)** (IHME). Not microdata, but modeled prevalence and burden of depression, anxiety, and other disorders for 204 countries by age (including 10-19), 1990-2021. Free with registration; good for context and prevalence. <span class="ds-youth">youth</span>
- **[DHS - Demographic and Health Surveys](https://dhsprogram.com/data/)**. A new optional mental-health module (PHQ-9 + GAD-7, ages 15-49) has so far been fielded in only a couple of surveys (Nepal and Mozambique, 2022); most DHS surveys carry no mental-health content. Free with registration. <span class="ds-youth">youth</span>

**United States**

- **[Add Health](https://addhealth.cpc.unc.edu/data/)** (UNC). CES-D depression and suicidal-ideation items; a cohort followed from grades 7-12 (1994-95) into adulthood. Free public-use subsample; the full sample is restricted-use. <span class="ds-youth">youth</span>
- **[NSDUH - National Survey on Drug Use and Health](https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/datafiles)** (SAMHSA). Kessler K6 distress, a major-depressive-episode module for adults and adolescents, and suicidality; ages 12+, annual. Free public-use files. <span class="ds-youth">youth</span>
- **[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm)** (CDC). PHQ-9 depression screener; the free public file covers adults 18+ (the 12-17 youth screener is restricted to the NCHS Research Data Center). Free public download.
- **[NCS-R / NCS-A](https://www.icpsr.umich.edu/web/ICPSR/studies/20240)** (Harvard / ICPSR). CIDI diagnostic interviews for DSM-IV disorders; the adult NCS-R has a free public-use route, the adolescent supplement NCS-A (ages 13-18) is restricted-use. <span class="ds-youth">youth</span>
- **[HRS - Health and Retirement Study](https://hrsdata.isr.umich.edu/data-products/public-survey-data)** (Michigan). CES-D-8 depression, biennial since 1992, ages 51+ (not a youth source). Free with registration.

**UK and Europe**

- **[Understanding Society (UKHLS)](https://www.understandingsociety.ac.uk/)** (UK). GHQ-12 and SWEMWBS wellbeing for adults (16+), plus a dedicated youth panel (ages 10-15) with the SDQ; annual since 2009. Free with registration (UK Data Service). <span class="ds-youth">youth</span>
- **[UK Biobank](https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/)**. A rich mental-health questionnaire (PHQ-9, GAD-7, CIDI-SF, AUDIT) for adults 40-69. Application, fee, and data-transfer agreement (not a free download).
- **[ELSA - English Longitudinal Study of Ageing](https://www.elsa-project.ac.uk/accessing-elsa-data)**. CES-D-8 depression and quality-of-life measures, ages 50+. Free with registration.
- **[SHARE](https://share-eric.eu/data/data-access)** (Europe). EURO-D depression across ~28 countries, ages 50+. Free for scientific use with registration.
- **[HBSC - Health Behaviour in School-aged Children](https://www.uib.no/en/hbscdata)** (WHO). Adolescents 11/13/15 across 50+ countries, but its mental-health content is self-reported wellbeing indicators (a psychosomatic-complaints scale and Cantril life-satisfaction), not a clinical scale; aggregate results are public, microdata is by request after an embargo. <span class="ds-youth">youth</span>

**Subjective wellbeing** (life satisfaction and happiness, not clinical mental health)

- **[Gallup World Poll](https://www.gallup.com/analytics/318923/world-poll-public-datasets.aspx)**. The Cantril life-evaluation ladder and daily affect for 140+ countries (ages 15+), annual since 2005-06. Respondent-level microdata is by paid subscription; some partner datasets and country aggregates are free.
- **[World Values Survey](https://www.worldvaluessurvey.org/)**. Life-satisfaction and happiness items for ~100 countries, ages 18+. Free with registration.

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
