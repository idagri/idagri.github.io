---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
/* Research page: topical tag in a left gutter, title-first typography. IDNS viridis palette. */
.rsch-key{ font-size:.8rem; margin:.3rem 0 1.6rem; }
.rsch-key b{ font-weight:600; }
.tag{ display:inline-block; font-size:.6rem; font-weight:700; letter-spacing:.04em; text-transform:uppercase;
  padding:.12rem .5rem; border-radius:1rem; white-space:nowrap; border:1px solid transparent; line-height:1.5; }
.tag.urban  { background:rgba(59,82,139,.12);  color:#33477a; border-color:rgba(59,82,139,.30); }
.tag.well   { background:rgba(33,145,140,.14); color:#13716b; border-color:rgba(33,145,140,.35); }
.tag.method { background:rgba(68,1,84,.10);    color:#5a3168; border-color:rgba(68,1,84,.25); }

.pub{ display:grid; grid-template-columns:8.5rem 1fr; gap:.15rem 1.3rem; align-items:start; margin:0 0 1.5rem; }
.pub-tag{ padding-top:.25rem; display:flex; flex-direction:column; gap:.12rem; align-items:flex-start; }
.pub-body{ min-width:0; }
.pub-title{ margin:0 0 .25rem; font-size:1.02rem; font-weight:700; line-height:1.35; }
.pub-flag{ display:inline-block; font-size:.62rem; font-weight:700; text-transform:uppercase; letter-spacing:.05em;
  color:#fff; background:#3B528B; border:none; border-radius:1rem; padding:.12rem .6rem; margin-left:.45rem; vertical-align:middle; }
.pub-flag.pre{ background:#6a7480; }
.pub-btn{ display:inline-block; font-size:.6rem; font-weight:700; letter-spacing:.05em; text-transform:uppercase;
  color:#13716b; background:rgba(33,145,140,.10); border:1px solid var(--vir-teal); border-radius:1rem;
  padding:.08rem .5rem; margin-left:.4rem; vertical-align:middle; white-space:nowrap; }
.pub-btn:hover{ background:var(--vir-teal); color:#fff; }
.pub-btn .fa-fw{ font-size:.9em; margin-right:.2em; }
/* All meta/note text shares ONE neutral gray (#6b6b6b), set apart from the black title. Sizes:
   authors, journal, status, and abstract at .85rem; funding and presentations sit smaller at .72rem.
   The journal was previously unsized (theme default, oversized) and black; it now matches the rest. */
.pub-meta{ margin:0; font-size:.85rem; color:#6b6b6b; line-height:1.5; }
.pub-journal{ margin:.15rem 0 .5rem; font-size:.85rem; color:#6b6b6b; line-height:1.45; }
.pub-journal em{ font-style:italic; }
.pub-fund{ margin:.2rem 0 0; font-size:.72rem; color:#6b6b6b; }
.pub-status{ margin:.2rem 0 0; font-size:.85rem; color:#6b6b6b; font-style:italic; }
.pub details{ margin:.5rem 0 0; }
.pub summary{ font-size:.85rem; cursor:pointer; color:#6b6b6b; }
.pub details p{ font-size:.72rem; line-height:1.55; margin:.4rem 0 0; color:#6b6b6b; }
/* Conference presentations: the smaller, tertiary tier, same gray, with a paragraph-space above. */
.pub-pres{ margin:.5rem 0 0; font-size:.72rem; color:#6b6b6b; }

@media (max-width:50em){
  .pub{ grid-template-columns:1fr; gap:.3rem; }
  .pub-tag{ flex-direction:row; padding-top:0; }
}

html[data-theme="dark"] .tag.urban  { background:rgba(110,140,210,.18); color:#aebfe6; border-color:rgba(110,140,210,.4); }
html[data-theme="dark"] .tag.well   { background:rgba(45,170,160,.20);  color:#6fd0c8; border-color:rgba(45,170,160,.4); }
html[data-theme="dark"] .tag.method { background:rgba(160,110,180,.20); color:#caa6da; border-color:rgba(160,110,180,.4); }
html[data-theme="dark"] .pub-btn{ color:#6fd0c8; background:rgba(45,170,160,.15); border-color:rgba(45,170,160,.5); }
html[data-theme="dark"] .pub-btn:hover{ background:#2daaa0; color:#0d1520; }
html[data-theme="dark"] .pub-meta, html[data-theme="dark"] .pub-journal, html[data-theme="dark"] .pub-fund, html[data-theme="dark"] .pub-status, html[data-theme="dark"] .pub-pres, html[data-theme="dark"] .pub summary, html[data-theme="dark"] .pub details p{ color:#b5b5b5; }
/* clickable topic filter */
.rsch-key .tag{ cursor:pointer; user-select:none; }
.rsch-key .tag-active{ box-shadow:0 0 0 2px currentColor inset; }
.tag.all{ background:#ececec; color:#555; border-color:#cfcfcf; }
html[data-theme="dark"] .tag.all{ background:#333a44; color:#cbd2da; border-color:#454e59; }
.pub{ transition:opacity .2s; }
.pub.pub-dim{ opacity:.15; }
.pub-tag .tag.tag-off{ display:none; }  /* when a topic filter is active, hide a multi-tag paper's other-topic tags */
</style>

**Fields:** Development Economics · Urban Economics · Behavioral Economics

**Profiles:** [Google Scholar](https://scholar.google.com/citations?user=WXqdhzsAAAAJ)

<p class="rsch-key"><b>Research topics</b> <span style="opacity:.55">(click to filter)</span>&nbsp; <span class="tag all tag-active" role="button" tabindex="0">All</span> <span class="tag urban" role="button" tabindex="0">Urban &amp; Migration</span> <span class="tag well" role="button" tabindex="0">Wellbeing &amp; Education</span> <span class="tag method" role="button" tabindex="0">Methods &amp; Replication</span></p>

---

## Working Papers

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Agricultural Productivity and Urbanization: Evidence from Indonesia's Transmigration Program <span class="pub-flag">Job Market Paper</span></p>
<p class="pub-meta">Solo-authored</p>
<p class="pub-status">Draft available upon request.</p>
<p class="pub-fund">Funding: STEG PhD Research Grant ($19,000); IHS Research &amp; Travel Grants ($12,800)</p>
<details><summary>Abstract</summary><p>I ask whether agricultural productivity in rural areas affects outcomes in cities located elsewhere. Two channels are at play: a price effect working through trade in food, and a wage effect working through migration. I separate the two using Indonesia's Transmigration Program, which resettled over two million people from Java and Bali to new agricultural villages, generating as-good-as-random variation in the productivity of the villages surrounding each city. Cities surrounded by more productive villages grow in population, agricultural employment falls, and modern-sector employment grows, in levels and shares. New arrivals cannot account for the shift, and the settlers largely stay in their villages, so previous urban residents must be switching sectors. The effects concentrate in cities less connected to global markets, which rely more on food from the hinterland. When cities lack sufficient access to food, investments in rural areas have more direct impacts on the structure of urban economies.</p></details>
<p class="pub-pres">Presented at: CEGA Research Retreat (R²), UC Berkeley (2026, upcoming); UEA North American Meeting, Federal Reserve Bank of Chicago (2026, upcoming); 10th Urbanization &amp; Development Conference, World Bank, Washington DC (2026); PacDev, UC Davis (2026); Development and Political Economics PhD Student Conference (DevPEC), Stanford (2026); UEA PhD Summer School, LSE (2026); University of Melbourne (2026); CEPR Paris Symposium, Paris (2025); University of Hawaii Applied Seminar (2025); Lindau Nobel Laureates Meeting, Germany (2025); IHS Migration Workshop, UC Davis (2025); Cities &amp; Development Workshop, Harvard (2024); IHS Trade Workshop, Harvard (2024); Economics of Migration Summer School, Mexico (2024)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Violence and Education in Rio: The Effect of Crime Exposure on University Entrance Exam Scores</p>
<p class="pub-meta">with <a href="https://sites.google.com/view/viniciuspecanha/home">Vinicius Peçanha</a></p>
<p class="pub-status">Draft available upon request.</p>
<p class="pub-fund">Funding: Weiss Fund ($12,900); IHS Research &amp; Travel Grant; Jacobs Social Impact Summer Research Grant ($6,000)</p>
<details><summary>Abstract</summary><p>A single high-stakes exam decides college access in much of the world, and in many cities of the Global South gun violence is routine in the weeks students sit it. We link shootings near Rio de Janeiro schools to an administrative panel that follows students from elementary school through college, comparing schools with a shooting shortly before Brazil's national exam (ENEM) to schools with one shortly after. Exposure lowers math scores by up to 0.2 of a standard deviation, yet on-time college entry does not move: we rule out effects larger than about 3 percentage points. The composition of entry changes instead: enrollment shifts from public into private institutions, student financing rises, and entrants avoid flagship public universities, consistent with Brazil's threshold-based admission rules. A few days of violence leaves the level of college access intact while durably re-sorting who pays for college, in which sector, and on what timeline.</p></details>
<p class="pub-pres">Presented at: LACEA-LAMES Annual Meeting, Lima, Peru (2026, upcoming); Workshop on the Economics of Education, Universidad de los Andes, Santiago, Chile (2024); Urban Economics Association, Washington DC (2022); International &amp; Development Economics Summer School, Italy (2022)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Economic Consequences of Improving Sleep Among the Poor through Cognitive Behavioral Therapy for Insomnia</p>
<p class="pub-meta">with <a href="https://sites.google.com/view/michelleescobar/main">Michelle Escobar Carias</a>, <a href="https://www.jpablofranco.com">Juan Pablo Franco</a>, and <a href="https://research.monash.edu/en/persons/sean-drummond/">Sean Drummond</a></p>
<p class="pub-status">Data collection in progress (summer-fall 2026)</p>
<p class="pub-fund">Funding: Weiss Fund ($24,400); CEGA Development Challenge ($20,000)</p>
<details><summary>Abstract</summary><p>Up to one in three adults report insomnia symptoms; the burden falls hardest on the urban poor. Whether poor sleep helps keep poor people poor is untested: the one field experiment raising sleep among low-income workers added time in bed without adding quality, and found no gains in cognition, productivity, or earnings. We ask whether the constraint is instead sleep quality, and test it with Cognitive Behavioral Therapy for Insomnia (CBT-I), the clinical first-line treatment, which raises sleep efficiency while leaving sleep time roughly unchanged: any economic effect cannot come from more hours of sleep. We randomize 300 adults with insomnia symptoms in Nairobi to four weeks of lay-facilitated group CBT-I or an active control matched on time and attention, with pre-registered endpoints spanning sleep, mental health, cognition, and economic outcomes. To our knowledge, this is the first adult randomized trial of CBT-I in sub-Saharan Africa.</p></details>
<p class="pub-pres">Presented at: Advances with Field Experiments (AFE) Conference, Chicago (2026, upcoming)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Rural Spillovers of Urban Growth in India</p>
<p class="pub-meta">with <a href="https://samuelasher.com/">Sam Asher</a>, <a href="https://www.jpchauvin.com/">Juan Pablo Chauvin</a>, and <a href="http://paulnovosad.com/">Paul Novosad</a></p>
<p class="pub-status">Draft available upon request.</p>
<p class="pub-fund">Funding: IHS Humane Studies Fellowships ($9,500, 2023-2025)</p>
<details><summary>Abstract</summary><p>We estimate the causal effect of urban employment growth on the rural economies surrounding Indian cities, asking whether villages share in the gains from urban expansion or lose their people and activity to it. We link roughly 1,500 cities, delineated by their built-up boundaries, to more than 250,000 villages, and instrument nearby urban employment growth with a shift-share design based on national industry shocks. Urban growth moves the village economy in two opposite directions: a 10-percentage-point increase in nearby urban employment growth lowers village population growth by about 1.1 percentage points over a decade while raising village employment growth by about 9 percentage points, with the gains led by services and reaching villages up to 100 km away. Growing cities slow population growth in the villages around them while expanding their non-farm economies.</p></details>
<p class="pub-pres">Presented at: European Meeting of the Urban Economics Association (EMUEA), Barcelona (2026)</p>
</div>
</div>

---

## Publications

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Beliefs, Information Sharing, and Mental Health Care Use Among University Students <a class="pub-btn" href="/papers/2026-06-JDE-Beliefs--information-sharing--and-mental-health-care.pdf"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i>PDF</a> <a class="pub-btn" href="https://doi.org/10.1016/j.jdeveco.2025.103646"><i class="fas fa-fw fa-link" aria-hidden="true"></i>Link</a></p>
<p class="pub-meta">with <a href="https://alisher-batmanov.github.io/">Alisher Batmanov</a>, <a href="https://www.bruno-calderon.com/">Bruno Calderon-Hernandez</a>, <a href="https://robertoglz.github.io/">Roberto Gonzalez-Tellez</a>, and <a href="https://research.tec.mx/vivo-tec/display/PID_316616">Alejandro Guardiola-Ramirez</a> · <a href="https://www.socialscienceregistry.org/trials/14804">Pre-registration</a></p>
<p class="pub-journal"><em>Journal of Development Economics</em> 180: 103646 (2026)</p>
<p class="pub-fund">Funding: Weiss Fund ($14,300); UC-MX Alianza Field Research Grant ($7,600); IHS Travel Research Grants ($7,000, 2023-2024)</p>
<details><summary>Abstract</summary><p>This paper investigates the role of beliefs and stigma in shaping students' use of professional mental health services at a large private university in Mexico, where services are readily accessible. In a survey experiment with 680 students, we find that nearly 50% of students in distress do not receive professional support despite high awareness and perceived effectiveness, a substantial treatment gap. We document stigmatized beliefs correlated with this gap: three-quarters of students incorrectly believe that those in distress perform worse academically and that most students going to therapy are in severe distress. An information intervention correcting these beliefs increases students' sharing of on-campus mental health resources with peers and their willingness to recommend these resources to a friend in distress, yet it lowers willingness to pay for private therapy and does not reduce self-reported therapy use six months later.</p></details>
<p class="pub-pres">Presented at: Melbourne Institute (2026); Advances with Field Experiments (AFE) Conference (2025); Field Experiments in Developing Countries (SEEDEC), Norway (2024); IEPS Seminar, Brazil (2024); UCSD-ITAM Collaborative Workshop, UC San Diego (2023); ITAM Applied Econometrics guest lecture (2023)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag method">Methods &amp; Replication</span></div>
<div class="pub-body">
<p class="pub-title">Reproducibility and Robustness of Economics and Political Science Research <a class="pub-btn" href="https://doi.org/10.1038/s41586-026-10251-x"><i class="fas fa-fw fa-link" aria-hidden="true"></i>Link</a></p>
<p class="pub-meta">with <a href="https://sites.google.com/site/abelbrodeur/">Abel Brodeur</a>, <a href="https://sites.google.com/view/derekmikola/">Derek Mikola</a>, <a href="https://sites.google.com/site/nikolaimcook/home">Nikolai Cook</a>, et al. (Institute for Replication)</p>
<p class="pub-journal"><em>Nature</em> 652(8108): 151-156 (2026)</p>
<details><summary>Abstract</summary><p>Reproducibility efforts strengthen science by testing the reliability of published findings and promoting self-correction. Computational reproductions, whereby independent researchers reproduce the results of published studies, are an essential diagnostic tool. We reproduced original analyses and conducted robustness checks of 110 articles published in leading economics and political science journals with mandatory data- and code-sharing policies. More than 85% of published claims were computationally reproducible. In robustness checks, 72% of statistically significant estimates remained significant and in the same direction, and the median reproduced effect size was 99% of the originally published effect size. Six independent research teams then examined 12 pre-specified hypotheses about the determinants of robustness: teams with more experience found lower levels of robustness, and robustness did not correlate with author characteristics or data availability.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag method">Methods &amp; Replication</span></div>
<div class="pub-body">
<p class="pub-title">AI-Assisted Teams Outperform AI-Led Teams but Not Human-Only Teams in Assessing Research Reproducibility in Quantitative Social Science <a class="pub-btn" href="https://doi.org/10.1073/pnas.2524747123"><i class="fas fa-fw fa-link" aria-hidden="true"></i>Link</a></p>
<p class="pub-meta">with <a href="https://sites.google.com/site/abelbrodeur/">Abel Brodeur</a>, <a href="https://valenta.dev/">David Valenta</a>, <a href="http://alexandrumarcoci.com/">Alexandru Marcoci</a>, et al. (Institute for Replication)</p>
<p class="pub-journal"><em>Proceedings of the National Academy of Sciences (PNAS)</em> 123(22): e2524747123 (2026)</p>
<details><summary>Abstract</summary><p>Large language models (LLMs) such as ChatGPT are transforming how scientists conduct and validate research, yet computational reproducibility and error detection remain expensive and labor-intensive. We experimentally test how collaboration between researchers and LLM assistants influences the reproduction of quantitative social science findings. We randomly assigned 288 researchers to 103 teams working under three conditions: human-only, AI-assisted (ChatGPT as a collaborative tool), or AI-led (ChatGPT with minimal human oversight). Teams reproduced published results from leading social science journals, detected coding errors, and proposed robustness checks. Human-only and AI-assisted teams achieved comparable reproduction rates (94% vs. 91%), and human-only teams identified more major coding errors. Both substantially outperformed AI-led teams, which achieved a 37% reproduction rate, detected fewer errors, and proposed weaker robustness checks. Expert human judgment currently remains indispensable for reliable empirical verification.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Stay-at-Home Orders, Social Distancing, and Trust <a class="pub-btn" href="https://link.springer.com/article/10.1007/s00148-021-00848-z"><i class="fas fa-fw fa-link" aria-hidden="true"></i>Link</a></p>
<p class="pub-meta">with <a href="https://sites.google.com/site/abelbrodeur/">Abel Brodeur</a> and <a href="https://sites.google.com/georgetown.edu/lamiskattan/home">Lamis Kattan</a></p>
<p class="pub-journal"><em>Journal of Population Economics</em> 34(4): 1321-1354 (2021)</p>
<details><summary>Abstract</summary><p>A clear understanding of community response to government decisions is crucial for policy makers and health officials during the COVID-19 pandemic. In this study, we document the determinants of implementation and compliance with stay-at-home orders in the USA, focusing on trust and social capital. Using cell phone data measuring changes in non-essential trips and average distance traveled, we find that mobility decreases significantly more in high-trust counties than in low-trust counties after the stay-at-home orders are implemented, with larger effects for more stringent orders. We also provide evidence that the estimated effect on post-order compliance is especially large for confidence in the press and governmental institutions, and relatively smaller for confidence in medicine and in science.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">The Price Ripple Effect in the Vancouver Housing Market <a class="pub-btn" href="https://doi.org/10.1080/02723638.2019.1567202"><i class="fas fa-fw fa-link" aria-hidden="true"></i>Link</a></p>
<p class="pub-meta">with <a href="https://blogs.ubc.ca/dley/">David Ley</a></p>
<p class="pub-journal"><em>Urban Geography</em> 40(8): 1171-1189 (2019)</p>
<p class="pub-fund">Funding: Neighborhood Change Research Grant ($11,000)</p>
<details><summary>Abstract</summary><p>Models of housing market dynamics examine the spatial diffusion of price changes from an epicenter through a regional or national network of geographic units. Less common has been the study of a ripple effect of price changes within a single metropolitan area, with implications for the erosion of residential affordability. Such trends have particular salience in the Vancouver metropolitan area, the least affordable housing market in North America. Using quarterly price data from local real estate boards, we examine price changes through municipal regions from 2005-2017, a period including several externally-induced price shocks. A time lag of three months consistently exists in the communication of price shocks from an originating epicenter to other parts of the metropolitan region, with longer lags for several more distant municipalities, confirming the presence of an intra-metropolitan ripple effect.</p></details>
</div>
</div>

---

## Under Review

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Out-of-Class Assignments versus Midterms: Shifting Grade-Weights to Improve Learning</p>
<p class="pub-meta">with <a href="https://econweb.ucsd.edu/~kantonov/">Kate Antonovics</a> and <a href="https://econweb.ucsd.edu/~mfamulari/">Melissa Famulari</a> · Revise &amp; Resubmit, <em>Journal of Economic Education</em> (2025)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Income Strongly Moderates Climate-Driven Migration <a class="pub-btn" href="https://eartharxiv.org/repository/view/11088/"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i>PDF</a></p>
<p class="pub-meta">with <a href="https://gps.ucsd.edu/faculty-directory/gaurav-khanna.html">Gaurav Khanna</a>, <a href="https://ppolonik2.github.io/">Pascal Polonik</a>, <a href="https://jessicaswan.github.io/">Jessica Wan</a>, <a href="https://jacopolunghi.github.io/">Jacopo Lunghi</a>, and <a href="https://katericke.com/">Katharine Ricke</a> · R&amp;R at <em>PNAS</em> (2025)</p>
</div>
</div>

---

## Work in Progress

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">You're Better Than You Think: Does Revealing Hidden Talent with a Novel Assessment Improve Student Outcomes?</p>
<p class="pub-meta">with <a href="https://sites.google.com/view/michelleescobar/main">Michelle Escobar Carias</a></p>
<p class="pub-fund">Funding: NBER PhD Dissertation Fellowship on Identifying &amp; Nurturing Math Talent ($36,000)</p>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Coping with Chronic Stress: Socio-Emotional Training for Frontline Workers</p>
<p class="pub-meta">with <a href="https://sites.google.com/view/michelleescobar/main">Michelle Escobar Carias</a> · <a href="https://www.socialscienceregistry.org/trials/18308">Pre-registration</a></p>
<p class="pub-status">Data collection in progress (summer-fall 2026)</p>
<details><summary>Abstract</summary><p>Essential public-sector workers in low- and middle-income countries (teachers, health workers, police officers) operate under chronic stress, exposure to community violence, and institutional neglect of their mental health. Burnout, anxiety, and untreated trauma are pervasive among these frontline workers, yet rigorous evidence on scalable interventions to support their wellbeing remains nearly nonexistent. This gap matters not only to the workers themselves, but also to the quality of public services they deliver. We provide experimental evidence on whether socio-emotional resilience training can improve the mental health and professional effectiveness of essential workers, focusing on public school teachers in Guatemala. We evaluate SanaMente, a trauma-informed training program that builds skills in stress recognition, emotional regulation, and supportive workplace practices, using a school-level cluster-randomized trial across 120 schools targeting 600 teachers in three municipalities in Guatemala.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag well">Wellbeing &amp; Education</span></div>
<div class="pub-body">
<p class="pub-title">Importance of Peers in Teaching: A Peer-Support Intervention on a Tutoring Platform <a class="pub-btn" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5552038"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i>PDF</a></p>
<p class="pub-meta">with <a href="https://alisher-batmanov.github.io/">Alisher Batmanov</a> · SSRN Working Paper (2025)</p>
<details><summary>Abstract</summary><p>We design and test a novel tutor-training intervention on a tutoring platform, with a focus on peer-group discussions. Roughly 2,000 university-student volunteer tutors lead math sessions for around 8,000 schoolchildren. By comparing Social and Emotional Learning (SEL) training with and without peer-group discussions, we isolate the role of peer connections in improving teaching, self-confidence, and communication. Pilot results indicate that students assigned to tutors who participated in peer-group discussions show larger gains in endline math scores than those whose tutors trained individually or without SEL training; tutors trained in peer groups also feel more connected and supported.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Migrant Protection Protocols ("Remain in Mexico") and Procedural Fairness in U.S. Immigration Courts</p>
<p class="pub-meta">with <a href="https://sites.ucmerced.edu/amuedo-dorantes/">Catalina Amuedo-Dorantes</a></p>
<p class="pub-fund">Funding: IHS Mentorship Grant ($8,000)</p>
<details><summary>Abstract</summary><p>The Migrant Protection Protocols (MPP, "Remain in Mexico") required non-Mexican asylum seekers arriving at the U.S.&ndash;Mexico border to wait in Mexico during their immigration court proceedings. Using administrative case-level microdata from the Executive Office for Immigration Review covering over one million cases from 2012 to 2020, we estimate the causal effect of MPP on procedural-fairness outcomes with an event-study difference-in-differences design, comparing non-Mexican (treated) and Mexican (control) respondents in courts operating MPP dockets. MPP led to a sharp decline in legal representation, a large increase in in-absentia removal orders, higher removal rates, shorter case durations, and a temporary surge in case terminations, concentrated among nationals of Honduras, Guatemala, and El Salvador. The findings indicate that MPP systematically undermined procedural fairness, creating a two-tiered system in which structural barriers, not individual choices, drove adverse case outcomes.</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag method">Methods &amp; Replication</span></div>
<div class="pub-body">
<p class="pub-title">Robustness in Empirical Economics: A Meta-Reproduction of 66 Articles from Leading Journals</p>
<p class="pub-meta">with <a href="https://www.rwi-essen.de/en/rwi/team/person/joerg-ankel-peters">Jörg Ankel-Peters</a>, <a href="https://www.rwi-essen.de/en/rwi/team/person/gunther-bensch">Gunther Bensch</a>, <a href="https://sites.google.com/site/abelbrodeur/">Abel Brodeur</a>, et al. · Mimeo (2026)</p>
</div>
</div>

---

## Pre-PhD Research

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">The Latin American Urbanization Puzzle: Structural Transformation and the Colonial Past</p>
<p class="pub-meta">M.A. thesis, University of British Columbia</p>
<details><summary>Abstract</summary><p>The most urbanized continent, Latin America lags on the economic development expected of its high urbanization rates. Across the region, I find that while industrialization and resource rents explain some variation, they are insufficient to account for exceptionally high urbanization. I present suggestive evidence that the colonial past created an urban system later conducive to "urbanization without growth."</p></details>
</div>
</div>

<div class="pub">
<div class="pub-tag"><span class="tag urban">Urban &amp; Migration</span></div>
<div class="pub-body">
<p class="pub-title">Factors of Urban Income Inequality in High- and Middle-Income Countries</p>
<p class="pub-meta">B.A. thesis, NRU Higher School of Economics · ECINEQ Conference Working Paper, Paris (2019)</p>
<details><summary>Abstract</summary><p>Inequality is widely studied within and across countries, but much less is known about inequality between the leading cities of different countries. I study an international cross-section of leading cities in high- and middle-income countries and propose a measure of the gap between a major city's per capita income and its country's national average. Since 2010 most countries in the sample have been catching up with their leading cities, consistent with cities acting as engines of growth. Reading the cross-section through a structural transformation lens, and clustering cities by a principal component approach, I find convergence both between clusters of developed- and developing-country cities and within clusters of similarly developed cities. Cities growing faster in population and per capita income show a wider city-country gap, while a stronger national economy and a larger primary-sector share in city output narrow it.</p></details>
</div>
</div>

<script>
(function(){
  var key=document.querySelector('.rsch-key'); if(!key) return;
  var pubs=[].slice.call(document.querySelectorAll('.pub'));
  var topics=['urban','well','method'];
  var tags=[].slice.call(key.querySelectorAll('.tag'));
  var allBtn=key.querySelector('.tag.all');
  var pubTags=[].slice.call(document.querySelectorAll('.pub-tag .tag'));
  function clear(){ pubs.forEach(function(p){p.classList.remove('pub-dim');}); pubTags.forEach(function(t){t.classList.remove('tag-off');}); tags.forEach(function(t){t.classList.remove('tag-active');}); key.removeAttribute('data-active'); if(allBtn) allBtn.classList.add('tag-active'); }
  function apply(topic){ pubs.forEach(function(p){ var ts=p.querySelectorAll('.pub-tag .tag'); var match=false; for(var i=0;i<ts.length;i++){ if(ts[i].classList.contains(topic)){ match=true; ts[i].classList.remove('tag-off'); } else { ts[i].classList.add('tag-off'); } } if(match) p.classList.remove('pub-dim'); else p.classList.add('pub-dim'); }); }
  if(allBtn){
    allBtn.addEventListener('click',clear);
    allBtn.addEventListener('keydown',function(e){ if(e.key==='Enter'||e.key===' '){ e.preventDefault(); clear(); } });
  }
  tags.forEach(function(tag){ var t=null; for(var i=0;i<topics.length;i++){ if(tag.classList.contains(topics[i])) t=topics[i]; } if(!t) return;
    function toggle(){ if(key.getAttribute('data-active')===t){ clear(); } else { clear(); key.setAttribute('data-active',t); tag.classList.add('tag-active'); if(allBtn) allBtn.classList.remove('tag-active'); apply(t); } }
    tag.addEventListener('click',toggle);
    tag.addEventListener('keydown',function(e){ if(e.key==='Enter'||e.key===' '){ e.preventDefault(); toggle(); } });
  });
})();
</script>
