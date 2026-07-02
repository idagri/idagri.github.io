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
.ds-guide .ds-tbl{ table-layout:fixed; }
.ds-guide .ds-tbl th:nth-child(1){ width:26%; }
.ds-guide .ds-tbl th:nth-child(2){ width:24%; }
.ds-guide .ds-tbl th:nth-child(3){ width:12%; }
.ds-guide .ds-tbl th:nth-child(4){ width:13%; }
.ds-guide .ds-tbl th:nth-child(5){ width:13%; }
.ds-guide .ds-tbl th:nth-child(6){ width:12%; }
@media (max-width:40em){ .res-card.has-img img{ width:92px; height:68px; } .ds-guide .ds-tbl{ table-layout:auto; } }
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

Publicly available spatial and satellite data for development and urban research:

- **[GHS - Global Human Settlement Layer](https://human-settlement.emergency.copernicus.eu/)** (JRC / Copernicus). Global gridded data on the human presence, 1975 onward.
    - GHS-BUILT (built-up surface), GHS-POP (population grids), GHS-SMOD (settlement model / degree of urbanization), and GHS-UCDB (Urban Centre Database of consistently delineated cities).
- **[DHS - Demographic and Health Surveys](https://dhsprogram.com/)**. Household survey microdata across many developing countries; the geospatial program adds (randomly displaced) GPS cluster coordinates and covariates such as night lights. Confidential GPS data needs a short access request.
- **Night lights.** VIIRS and DMSP nighttime-lights rasters, a standard proxy for local economic activity (see Matt Lowe's night-lights and ArcGIS guide).
- **[GADM](https://gadm.org/)**. Administrative boundaries worldwide, country down to level 2-3.
- **[IPUMS International](https://international.ipums.org/international/geography_gis.shtml)**. Harmonized (consistent-over-time GEOLEV1 / GEOLEV2) and unharmonized (year-specific) administrative boundaries linked to census microdata; see the [GIS boundary files](https://international.ipums.org/international/gis.shtml). [IPUMS USA](https://usa.ipums.org/usa/) does the same for the US.
- **Aggregated catalogs.** The [UPenn Libraries GIS guide](https://guides.library.upenn.edu/c.php?g=1321452&p=9876288) (global and US spatial data) and the [geo4.dev data catalog](https://www.geo4.dev/library?cat=Data+Catalog) (development-focused) list many more sources.

</details>

<details class="ds-guide" markdown="1">
<summary><b>Mental health &amp; wellbeing data</b></summary>

Publicly available datasets with a validated mental-health or wellbeing measure, a few key economics papers with open replication data, and speech/audio depression corpora. Most datasets are free with registration; restricted or paid ones are flagged. The **Youth available?** column notes whether adolescents / young adults are covered: by age (a general sample you can filter), by student status, or as a youth-only sample.

**Development and low- or middle-income country panels**

| Dataset (measure) | Geographic coverage | Level | Total N | Youth available? | Access |
|---|---|---|---|---|---|
| **[IFLS](https://www.rand.org/health/surveys/FLS/IFLS/access.html)** - Indonesia Family Life Survey (CES-D-10) | Indonesia, 13 provinces; province-level (GPS restricted) | Individual &amp; household | ~30,000 individuals / 7,200+ households | Yes, age 15+ | Free, registration |
| **[MxFLS](https://www.ennvih-mxfls.org/english/)** - Mexican Family Life Survey (Zung/Calderon depression) | Mexico, national; state &amp; municipality | Individual &amp; household | ~35,000 individuals / 8,400 households | Yes, age 15+ | Free, registration |
| **[Young Lives](https://www.younglives.org.uk/)** (SRQ-20, Cantril, GAD-7/PHQ-8) | Ethiopia, India, Peru, Vietnam; region/district | Individual (child cohort) | ~12,000 children | Youth cohort (child to young adult) | Free, registration (UK Data Service) |
| **[NIDS](https://www.datafirst.uct.ac.za/dataportal/index.php/collections/NIDS)** - National Income Dynamics Study (CES-D-10) | South Africa, national; district municipality | Individual | ~28,000 individuals / 7,300 households | Yes, age 15+ | Free, registration |
| **[CFPS](https://opendata.pku.edu.cn/dataverse/CFPS)** - China Family Panel Studies (CES-D, K6) | China, 25 provinces (~95% of pop.) | Individual &amp; household | ~42,600 individuals / 14,960 households | Yes, age 10+ | Free, registration + data-use agreement |
| **[KLPS](https://dataverse.harvard.edu/dataverse/KLPS)** - Kenya Life Panel Survey (CES-D-10, KLPS-4) | Kenya, Busia County cohort (followed nationwide and abroad) | Individual (+ 2nd-gen children) | ~7,500 cohort + ~5,200 children | Yes (young-adult cohort) | Free, open (CC0) |
{: .ds-tbl}

**United States, UK &amp; Europe**

| Dataset (measure) | Geographic coverage | Level | Total N | Youth available? | Access |
|---|---|---|---|---|---|
| **[Add Health](https://addhealth.cpc.unc.edu/data/)** (CES-D depression) | US, national; geocodes restricted | Individual | ~20,000 (in-home) | Yes (adolescent cohort) | Public-use free; full sample restricted |
| **[NSDUH](https://www.samhsa.gov/data/data-we-collect/nsduh-national-survey-drug-use-and-health/datafiles)** - Nat. Survey on Drug Use &amp; Health (Kessler K6, MDE module) | US, national + state (small-area est.) | Individual | ~67,500 / year | Yes, age 12+ | Free public-use files |
| **[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm)** (PHQ-9) | US, national only in public file | Individual | ~5,000 / year | Yes (12-17 restricted) | Free (18+); 12-17 file restricted |
| **[NCS-R / NCS-A](https://www.icpsr.umich.edu/web/ICPSR/studies/20240)** (CIDI diagnostic) | US, national | Individual | 9,282 / 10,123 | Yes (NCS-A, 13-18) | NCS-R free; NCS-A restricted |
| **[HRS](https://hrsdata.isr.umich.edu/data-products/public-survey-data)** - Health &amp; Retirement Study (CES-D-8) | US, national | Individual | ~20,000 / wave | No (50+) | Free, registration |
| **[Healthy Minds Study](https://healthymindsnetwork.org/hms/)** (PHQ-9, GAD-7, flourishing) | US colleges; Census region only, individual colleges blinded | Individual (student) | ~935,000 (675+ colleges) | Students only (college) | Free, de-identified; short data-request form |
| **[Understanding Society](https://www.understandingsociety.ac.uk/)** (UKHLS) (GHQ-12, SWEMWBS; youth SDQ) | UK; region public, finer restricted | Individual &amp; household | ~40,000 households / ~100,000 individuals | Yes (youth panel 10-15) | Free, registration (UK Data Service) |
| **[ELSA](https://www.elsa-project.ac.uk/accessing-elsa-data)** - English Longitudinal Study of Ageing (CES-D-8) | England; region-level public | Individual | ~11,400 (Wave 1 core) | No (50+) | Free, registration |
| **[SHARE](https://share-eric.eu/data/data-access)** (EURO-D) | 28 European countries + Israel; country-level | Individual | ~160,000 respondents | No (50+) | Free (scientific use), registration |
| **[UK Biobank](https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/)** (PHQ-9, GAD-7, CIDI-SF) | UK; location restricted (1 km grid) | Individual | ~500,000 | No (40-69) | Application + fee + agreement |
{: .ds-tbl}

**Cross-national and global**

| Dataset (measure) | Geographic coverage | Level | Total N | Youth available? | Access |
|---|---|---|---|---|---|
| **[WHO World Mental Health](https://www.hcp.med.harvard.edu/wmh/)** (CIDI diagnostic) | 28+ countries; country-level | Individual | &gt;200,000 interviews | No (adults) | Restricted (consortium agreement) |
| **[HBSC](https://www.uib.no/en/hbscdata)** - Health Behaviour in School-aged Children (psychosomatic scale, Cantril; wellbeing) | 45+ countries; country/region | Individual (student) | ~220,000+ / round | Students only (ages 11/13/15) | Aggregate public; microdata by request (embargo) |
| **[Global Burden of Disease](https://vizhub.healthdata.org/gbd-results/)** (modeled prevalence &amp; burden) | 204 countries + some subnational | Country-year (aggregate) | Aggregate (not respondents) | Yes (age bands, incl. 10-19) | Free, registration |
| **[DHS](https://dhsprogram.com/data/)** - Demographic and Health Surveys (mental-health module: PHQ-9 + GAD-7) | Overall 63 countries (displaced GPS clusters); MH module in a small but growing set (Nepal, Kenya, Bangladesh, and others), not most surveys | Individual &amp; household | ~5,000-30,000 households / survey | Yes, age 15-49 | Free, registration |
{: .ds-tbl}

**Subjective wellbeing** (life satisfaction and happiness, not clinical mental health)

| Dataset (measure) | Geographic coverage | Level | Total N | Youth available? | Access |
|---|---|---|---|---|---|
| **[Gallup World Poll](https://www.gallup.com/analytics/318923/world-poll-public-datasets.aspx)** (Cantril ladder, daily affect) | 160+ countries; country-level | Individual | ~1,000 / country / year | Yes, age 15+ | Paid microdata; some free aggregates |
| **[World Values Survey](https://www.worldvaluessurvey.org/)** (life satisfaction, happiness) | 64 countries (Wave 7); country-level | Individual | ~95,000 / wave | No (18+) | Free, registration |
{: .ds-tbl}

**Key mental-health economics papers (with public replication data)**

| Paper | Year | Journal | Population | Intervention | Replication | Mental-health variables |
|---|---|---|---|---|---|---|
| **Haushofer &amp; Shapiro** | 2016 | QJE | Poor households, Kenya | RCT: unconditional cash transfers | [Harvard Dataverse](https://doi.org/10.7910/DVN/M2GAZN) | Psychological-wellbeing index: CES-D, Cohen stress, WVS happiness &amp; life satisfaction, salivary cortisol |
| **Baranov, Bhalotra, Biroli &amp; Maselko** | 2020 | AER | Perinatal mothers, rural Pakistan | RCT: perinatal CBT (Thinking Healthy) | [openICPSR](https://doi.org/10.3886/E111366V1) | SCID (major-depression diagnosis), Hamilton scale, disability, GAF, social support |
| **Bessone, Rao, Schilbach, Schofield &amp; Toma** | 2021 | QJE | Low-income adults, Chennai (India) | RCT: night-sleep devices / incentives; workplace naps | [Harvard Dataverse](https://doi.org/10.7910/DVN/GJ9QPC) | Psychological-wellbeing index: depression, stress, happiness, life satisfaction, Cantril ladder |
| **Banerjee, Duflo, McKelway, Schilbach et al.** | 2023 | Ann. Intern. Med. | Elderly living alone, Tamil Nadu (India) | RCT: phone-based CBT; one-time cash transfer | [Harvard Dataverse](https://doi.org/10.7910/DVN/SXEYFW) | Geriatric Depression Scale, WHODAS, single-item loneliness |
| **Angelucci &amp; Bennett** | 2024 | AER | Adults with depression, Karnataka (India) | RCT: antidepressant pharmacotherapy; livelihood support | [openICPSR](https://doi.org/10.3886/E191402V1) | PHQ-9 (screening + severity) |

**Detecting depression from speech / audio** - public corpora, mostly from the speech-ML and clinical communities (I found no economics study that has released audio-based depression data):

- **[DAIC-WOZ / E-DAIC](https://dcapswoz.ict.usc.edu/)** (USC). Field-standard English corpus: clinical interviews, audio + transcripts, PHQ-8 labels (the AVEC benchmark). Free but restricted (signed application, institutional email).
- **[Androids Corpus](https://github.com/androidscorpus/data)**. Italian speech (reading + interview), clinician diagnoses; open direct download (academic terms).
- **[EATD-Corpus](https://github.com/speechandlanguageprocessing/ICASSP2022-Depression)**. Chinese speech + text with SDS depression labels; open download.
- **[MODMA](https://modma.lzu.edu.cn/data/index/)** (Lanzhou). Audio (+ EEG), clinical MDD diagnosis; free but account + agreement.

</details>

## Research Tools

<div class="res-card has-img">
<img loading="lazy" src="/images/res-stata-map.jpg" alt="A US choropleth map made with Stata's spmap">
<div>
<p class="rt"><a href="https://github.com/idagri/stata-tools">Stata tools and guides</a></p>
<p class="rd">Useful Stata tools with self-help guides, including making maps (SPMAP / GRMAP) and sample do-files.</p>
</div>
</div>

<div class="res-card has-img">
<img loading="lazy" src="/images/res-mapdigit.jpg" alt="A historical map being digitized">
<div>
<p class="rt"><a href="https://github.com/Xu-Haicheng/Digitizing-Historical-Maps-With-QGIS-and-Python/blob/main/Digitizing_Historical_Maps_Guide.ipynb">Digitizing historical maps with QGIS and Python</a></p>
<p class="rd">A step-by-step guide to georeferencing and digitizing historical maps (co-authored with a lab student).</p>
</div>
</div>

<div class="res-card has-img">
<img loading="lazy" src="/images/res-shrug.jpg" alt="Map of India showing distance to the nearest urban area">
<div>
<p class="rt"><a href="https://www.devdatalab.org/shrug">SHRUG: open geospatial data for India</a></p>
<p class="rd">The Socioeconomic High-resolution Rural-Urban Geographic Platform: open data covering roughly 600,000 villages and 8,000 towns in India, from the Development Data Lab.</p>
</div>
</div>
