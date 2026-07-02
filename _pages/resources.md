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
.ds-guide table{ font-size:.72rem; border-collapse:collapse; width:100%; margin:.5rem 0 1.1rem; }
.ds-guide th, .ds-guide td{ text-align:left; padding:.32rem .5rem; border-bottom:1px solid #e4e4e4; vertical-align:top; line-height:1.4; }
.ds-guide th{ font-weight:700; color:#13716b; border-bottom:2px solid rgba(33,145,140,.4); }
.ds-guide td a{ font-weight:600; }
@media (max-width:40em){ .res-card.has-img img{ width:92px; height:68px; } }
html[data-theme="dark"] .res-card .rd{ color:#b5b5b5; }
html[data-theme="dark"] .ds-youth{ color:#6fd0c8; background:rgba(45,170,160,.18); border-color:rgba(45,170,160,.4); }
html[data-theme="dark"] .ds-guide th, html[data-theme="dark"] .ds-guide td{ border-color:#3a3f48; }
html[data-theme="dark"] .ds-guide th{ color:#6fd0c8; }
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

<details class="ds-guide" markdown="1">
<summary><b>Mental health &amp; wellbeing data</b></summary>

Publicly available datasets that carry a validated mental-health or wellbeing measure, plus a few key economics papers with open replication data. Most datasets are free with registration; restricted or paid ones are flagged. The <span class="ds-youth">youth</span> tag marks samples that include adolescents or young adults (usable for student / youth mental-health research).

**Development and low- or middle-income country panels**

| Dataset (measure) | Geographic coverage | Unit of obs. | Total N | Youth | Access |
|---|---|---|---|---|---|
| **[IFLS](https://www.rand.org/health/surveys/FLS/IFLS/access.html)** - Indonesia Family Life Survey (CES-D-10) | Indonesia, 13 provinces; province-level (GPS restricted) | Households &amp; individuals (15+ for CES-D) | ~30,000 individuals / 7,200+ households | <span class="ds-youth">youth</span> | Free, registration |
| **[MxFLS](https://www.ennvih-mxfls.org/english/)** - Mexican Family Life Survey (Zung/Calderon depression) | Mexico, national; state &amp; municipality | Individuals in households (15+) | ~35,000 individuals / 8,400 households | <span class="ds-youth">youth</span> | Free, registration |
| **[Young Lives](https://www.younglives.org.uk/)** (SRQ-20, Cantril, GAD-7/PHQ-8) | Ethiopia, India, Peru, Vietnam; region/district | Index children, 2 cohorts | ~12,000 children | <span class="ds-youth">youth</span> | Free, registration (UK Data Service) |
| **[NIDS](https://www.datafirst.uct.ac.za/dataportal/index.php/collections/NIDS)** - National Income Dynamics Study (CES-D-10) | South Africa, national; district municipality | Individuals (15+) | ~28,000 individuals / 7,300 households | <span class="ds-youth">youth</span> | Free, registration |
| **[CFPS](https://opendata.pku.edu.cn/dataverse/CFPS)** - China Family Panel Studies (CES-D, K6) | China, 25 provinces (~95% of pop.) | Individuals &amp; households (10+) | ~42,600 individuals / 14,960 households | <span class="ds-youth">youth</span> | Free, registration + data-use agreement |

**Cross-national**

| Dataset (measure) | Geographic coverage | Unit of obs. | Total N | Youth | Access |
|---|---|---|---|---|---|
| **[WHO World Mental Health](https://www.hcp.med.harvard.edu/wmh/)** (CIDI diagnostic) | 28+ countries; country-level | Adults (mostly 18+) | &gt;200,000 interviews | — | Restricted (consortium agreement) |
| **[Global Burden of Disease](https://vizhub.healthdata.org/gbd-results/)** (modeled prevalence &amp; burden) | 204 countries + some subnational | Modeled location x year x age x sex | Aggregate (not respondents) | <span class="ds-youth">youth</span> | Free, registration |
| **[DHS](https://dhsprogram.com/data/)** - Demographic and Health Surveys (PHQ-9 + GAD-7; Nepal &amp; Mozambique 2022 only) | 63 countries; displaced GPS clusters | Individuals 15-49 | ~5,000-30,000 households / survey | <span class="ds-youth">youth</span> | Free, registration |

**United States**

| Dataset (measure) | Geographic coverage | Unit of obs. | Total N | Youth | Access |
|---|---|---|---|---|---|
| **[Add Health](https://addhealth.cpc.unc.edu/data/)** (CES-D depression) | US, national; geocodes restricted | Individuals, grades 7-12 into adulthood | ~20,000 (in-home) | <span class="ds-youth">youth</span> | Public-use free; full sample restricted |
| **[NSDUH](https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/datafiles)** - Nat. Survey on Drug Use &amp; Health (Kessler K6, MDE module) | US, national + state (small-area est.) | Individuals 12+ | ~67,500 / year | <span class="ds-youth">youth</span> | Free public-use files |
| **[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm)** (PHQ-9) | US, national only in public file | Individuals, all ages | ~5,000 / year | <span class="ds-youth">youth</span> | Free (18+); 12-17 file restricted |
| **[NCS-R / NCS-A](https://www.icpsr.umich.edu/web/ICPSR/studies/20240)** (CIDI diagnostic) | US, national | Individuals: adults / adolescents | 9,282 / 10,123 | <span class="ds-youth">youth</span> | NCS-R free; NCS-A restricted |
| **[HRS](https://hrsdata.isr.umich.edu/data-products/public-survey-data)** - Health &amp; Retirement Study (CES-D-8) | US, national | Adults 50+ | ~20,000 / wave | — | Free, registration |
| **[Healthy Minds Study](https://healthymindsnetwork.org/hms/)** (PHQ-9, GAD-7, flourishing) | US colleges; Census region only, individual colleges blinded | College / university students | ~935,000 (675+ colleges) | <span class="ds-youth">youth</span> | Free, de-identified; short data-request form |

**UK and Europe**

| Dataset (measure) | Geographic coverage | Unit of obs. | Total N | Youth | Access |
|---|---|---|---|---|---|
| **[Understanding Society](https://www.understandingsociety.ac.uk/)** (UKHLS) (GHQ-12, SWEMWBS; youth SDQ) | UK; region public, finer restricted | Households &amp; individuals (16+; youth 10-15) | ~40,000 households / ~100,000 individuals | <span class="ds-youth">youth</span> | Free, registration (UK Data Service) |
| **[ELSA](https://www.elsa-project.ac.uk/accessing-elsa-data)** - English Longitudinal Study of Ageing (CES-D-8) | England; region-level public | Adults 50+ | ~11,400 (Wave 1 core) | — | Free, registration |
| **[SHARE](https://share-eric.eu/data/data-access)** (EURO-D) | 28 European countries + Israel; country-level | Adults 50+ | ~160,000 respondents | — | Free (scientific use), registration |
| **[UK Biobank](https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/)** (PHQ-9, GAD-7, CIDI-SF) | UK; location restricted (1 km grid) | Adults 40-69 | ~500,000 | — | Application + fee + agreement |
| **[HBSC](https://www.uib.no/en/hbscdata)** - Health Behaviour in School-aged Children (psychosomatic scale, Cantril; wellbeing, not clinical) | 45+ countries; country/region | Students aged 11, 13, 15 | ~220,000+ / round | <span class="ds-youth">youth</span> | Aggregate public; microdata by request (embargo) |

**Subjective wellbeing** (life satisfaction and happiness, not clinical mental health)

| Dataset (measure) | Geographic coverage | Unit of obs. | Total N | Youth | Access |
|---|---|---|---|---|---|
| **[Gallup World Poll](https://www.gallup.com/analytics/318923/world-poll-public-datasets.aspx)** (Cantril ladder, daily affect) | 160+ countries; country-level | Adults 15+ | ~1,000 / country / year | <span class="ds-youth">youth</span> | Paid microdata; some free aggregates |
| **[World Values Survey](https://www.worldvaluessurvey.org/)** (life satisfaction, happiness) | 64 countries (Wave 7); country-level | Adults 18+ | ~95,000 / wave | — | Free, registration |

**Key mental-health economics papers (with public replication data)**

| Paper | Replication data | Mental-health variables |
|---|---|---|
| **Haushofer &amp; Shapiro (2016)**, *QJE* - unconditional cash transfers, Kenya | [Harvard Dataverse](https://doi.org/10.7910/DVN/M2GAZN) | Psychological-wellbeing index: CES-D depression, Cohen perceived stress, worries, WVS happiness &amp; life satisfaction, salivary cortisol; also Rosenberg self-esteem, LOT-R optimism |
| **Baranov, Bhalotra, Biroli &amp; Maselko (2020)**, *AER* - maternal-depression RCT, Pakistan | [openICPSR](https://doi.org/10.3886/E111366V1) | SCID (DSM-IV major-depression diagnosis), Hamilton Depression Scale (HAM-D severity), Brief Disability Questionnaire, GAF, social support (MSPSS) |
| **Angelucci &amp; Bennett (2024)**, *AER* - depression treatment, India | [openICPSR](https://doi.org/10.3886/E191402V1) | PHQ-9 depression (screening + severity); moderate/severe-depression indicator |
| **Banerjee, Duflo, McKelway, Schilbach et al. (2023)**, *Annals of Internal Medicine* - CBT + cash for elderly living alone, India | [Harvard Dataverse](https://doi.org/10.7910/DVN/SXEYFW) | Geriatric Depression Scale (GDS), WHODAS functional impairment, single-item loneliness |

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
