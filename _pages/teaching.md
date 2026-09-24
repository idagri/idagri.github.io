---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<style>
.tt{ border-collapse:collapse; width:100%; font-size:.85rem; margin:.5rem 0 .5rem; }
.tt th{ text-align:left; background:rgba(33,145,140,.12); color:#13716b; font-weight:700;
  padding:.32rem .55rem; border-bottom:2px solid rgba(33,145,140,.4);
  font-size:.66rem; text-transform:uppercase; letter-spacing:.03em; }
.tt td{ padding:.3rem .55rem; border-bottom:1px solid #ececec; vertical-align:top; line-height:1.35; }
.tt tr:hover td{ background:rgba(33,145,140,.04); }
/* Column widths: the course and theme columns were taking all the slack and pushing
   "Student / Instructor" onto a second line. Widths are set on the header cells because
   the body cells use rowspan, so nth-child does not line up on continuation rows. */
.tt th:nth-child(1){ width:46%; }
.tt th:nth-child(2){ width:24%; }
.tt th:nth-child(3){ width:11%; }
.tt th:nth-child(4){ width:19%; }
.tt td.yr{ white-space:nowrap; }
.tt td.evlinks{ white-space:nowrap; }
.tt .c-name{ font-weight:600; }
.tt .yr{ white-space:nowrap; }
.tt .lvl{ display:inline-block; font-size:.6rem; font-weight:700; text-transform:uppercase; letter-spacing:.04em;
  color:#2a5e7e; background:rgba(49,104,142,.12); border:1px solid rgba(49,104,142,.28); border-radius:999px;
  padding:.03rem .4rem; margin-left:.35rem; vertical-align:middle; white-space:nowrap; }
.tt.ins th{ background:rgba(49,104,142,.13); color:#2a5e7e; border-bottom-color:rgba(49,104,142,.45); }
.tt .grp td{ background:rgba(49,104,142,.09); font-weight:700; font-size:.64rem; text-transform:uppercase;
  letter-spacing:.04em; color:#2a5e7e; padding:.28rem .55rem; }
.tt .grp .grp-row{ display:flex; justify-content:space-between; align-items:baseline; gap:.5rem; flex-wrap:wrap; }
.tt .grp .grp-all{ flex:0 0 calc(19% - 1rem); text-align:left; line-height:1.35; text-transform:none; letter-spacing:0; font-weight:600; font-size:.72rem; color:#5b6470; }
.tt .grp .grp-all a{ color:#2c6e8f; white-space:nowrap; }
html[data-theme="dark"] .tt .grp .grp-all{ color:#aeb6c0; }
html[data-theme="dark"] .tt .grp .grp-all a{ color:#6fd0c8; }
.evlinks a{ white-space:nowrap; }
.tt .evlinks .ab{ font-size:.82em; color:#9099a3; }
html[data-theme="dark"] .tt .evlinks .ab{ color:#8f97a1; }
.cred li{ margin:.25rem 0; }
.award-row{ display:flex; gap:.55rem; align-items:flex-start; margin:.35rem 0; font-size:.92rem; }
.award-row .ic{ flex:0 0 auto; }
.note{ font-size:.82rem; color:#5b6470; }
.footnote{ font-size:.75rem; margin-top:.3rem; }
/* numbered footnotes under the tables (replaces the loose notes that used to pile up here) */
.fnref{ font-size:.62rem; font-weight:700; line-height:0; vertical-align:super; margin-left:.1em; }
.fnref a{ text-decoration:none; }
.fnotes{ font-size:.75rem; color:#5b6470; margin:.6rem 0 0; padding-left:1.2rem; }
.fnotes li{ margin:.2rem 0; padding-left:.15rem; }
/* Teaching evaluation summary: a small pill in the top right of the content column,
   set beside the first heading instead of the full-width banner it replaced. */
.eval-chip-wrap{ margin:0; }
.eval-chip{ float:right; display:inline-flex; align-items:center; gap:.35rem;
  margin:.9rem 0 .4rem .9rem; padding:.26rem .7rem; border-radius:999px;
  border:1px solid rgba(33,145,140,.35); background:rgba(33,145,140,.08);
  font-size:.76rem; font-weight:600; color:#13716b; text-decoration:none;
  white-space:nowrap; transition:background .15s ease; }
.archive a.eval-chip, .page__content a.eval-chip{ text-decoration:none; }  /* the theme underlines every content link; the pill reads as a button */
.eval-chip:hover{ background:rgba(33,145,140,.16); }
html[data-theme="dark"] .eval-chip{ color:#6fd0c8; background:rgba(45,170,160,.12); border-color:rgba(45,170,160,.32); }
@media (max-width:50em){ .tt{ font-size:.78rem; } .tt th,.tt td{ padding:.28rem .4rem; }
  .tt td.evlinks{ white-space:normal; } }
@media (max-width:40em){ .eval-chip{ float:none; margin:.2rem 0 .8rem; } .eval-chip-wrap{ text-align:center; } }
html[data-theme="dark"] .tt td{ border-color:#3a3a3a; }
html[data-theme="dark"] .tt th{ background:rgba(45,170,160,.18); color:#6fd0c8; }
html[data-theme="dark"] .tt.ins th{ background:rgba(110,140,210,.18); color:#aebfe6; }
html[data-theme="dark"] .tt .grp td{ background:rgba(110,140,210,.15); color:#aebfe6; }
html[data-theme="dark"] .tt .lvl{ color:#aebfe6; background:rgba(110,140,210,.16); border-color:rgba(110,140,210,.4); }
html[data-theme="dark"] .note{ color:#aaa; }
html[data-theme="dark"] .fnotes{ color:#aaa; }
</style>

<div class="eval-chip-wrap"><a class="eval-chip" href="/files/teaching-evaluation-summary.pdf"><span aria-hidden="true">📊</span> Teaching evaluation summary (PDF)</a></div>

## Instructor of record

I have been the **instructor of record** (Associate-In Instructor) for my own course **three times**, designing and delivering the full course:

<table class="tt ins">
<thead><tr><th>Course</th><th>Theme</th><th>Term</th><th>Evaluation</th></tr></thead>
<tbody>
<tr><td class="c-name">Applied Econometrics &amp; Data (ECON 121)</td><td>Econometrics</td><td class="yr">Summer 2025</td><td><a href="/files/evals/eval-ins-econ121-su2025.pdf">Student evals</a></td></tr>
<tr><td class="c-name">Introduction to Data Analysis for Economists (ECON 5)</td><td>Applied research &amp; data</td><td class="yr">Summer 2025</td><td><a href="/files/evals/eval-ins-econ5-su2025.pdf">Student evals</a></td></tr>
<tr><td class="c-name">Introduction to Data Analysis for Economists (ECON 5)</td><td>Applied research &amp; data</td><td class="yr">Summer 2024</td><td><a href="/files/evals/eval-ins-econ5-su2024.pdf">Student evals</a></td></tr>
</tbody>
</table>

## Awards

<div class="award-row"><span class="ic">🏅</span><span>Outstanding Summer Graduate Teaching Scholar Award, 2024 (one of five selected from 61 UCSD graduate instructors of record)</span></div>
<div class="award-row"><span class="ic">🏅</span><span>Graduate Associate-In Instructor in Economics Award, UCSD, 2024 and 2025</span></div>
<div class="award-row"><span class="ic">🏅</span><span>Killam Outstanding Graduate Teaching Assistant Award, UBC, 2019</span></div>

## Teaching assistant

<table class="tt">
<thead><tr><th>Course</th><th>Theme</th><th>Term</th><th>Evaluations<sup class="fnref"><a href="#fn1">1</a></sup></th></tr></thead>
<tbody>
<tr class="grp"><td colspan="4"><div class="grp-row"><span class="grp-name">UC San Diego</span><span class="grp-all">Combined PDF:<br><a href="/files/evals/student-evaluations-combined.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf">Instructor</a></span></div></td></tr>
<tr><td rowspan="3" class="c-name">Introduction to Data Analysis for Economists (ECON 5)</td><td rowspan="3">Applied research &amp; data</td><td class="yr">Spring 2026</td><td class="evlinks"><a href="/files/evals/eval-ta-econ5-sp2026.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=2">Instructor</a><sup class="fnref"><a href="#fn2">2</a></sup></td></tr>
<tr><td class="yr">Spring 2025</td><td class="evlinks"><a href="/files/evals/eval-ta-econ5-sp2025.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=3">Instructor</a></td></tr>
<tr><td class="yr">Winter 2023</td><td class="evlinks"><a href="/files/evals/eval-ta-econ5-wi2023.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=4">Instructor</a></td></tr>

<tr><td rowspan="4" class="c-name">Introduction to Research in Economics (ECON 190)</td><td rowspan="4">Applied research &amp; data</td><td class="yr">Winter 2026</td><td class="evlinks"><a href="/files/evals/eval-ta-econ190-wi2026.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=5">Instructor</a></td></tr>
<tr><td class="yr">Summer 2025</td><td class="evlinks"><a href="/files/evals/eval-ta-econ190-su2025.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=6">Instructor</a></td></tr>
<tr><td class="yr">Winter 2025</td><td class="evlinks"><a href="/files/evals/eval-ta-econ190-wi2025.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=7">Instructor</a></td></tr>
<tr><td class="yr">Winter 2024</td><td class="evlinks"><a href="/files/evals/eval-ta-econ190-wi2024.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=8">Instructor</a></td></tr>

<tr><td rowspan="2" class="c-name">GIS &amp; Spatial Data Analysis (GPEC 443) <span class="lvl">Graduate</span></td><td rowspan="2">Spatial data &amp; GIS</td><td class="yr">Fall 2025</td><td class="evlinks"><a href="/files/evals/eval-ta-gpec443-fa2025.pdf">Student</a></td></tr>
<tr><td class="yr">Fall 2024</td><td class="evlinks"><a href="/files/evals/eval-ta-gpec443-fa2024.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=9">Instructor</a></td></tr>

<tr><td rowspan="4" class="c-name">Intermediate Microeconomics (ECON 100A)</td><td rowspan="4">Microeconomics</td><td class="yr">Summer 2024</td><td class="evlinks"><a href="/files/evals/eval-ta-econ100a-su2024.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=11">Instructor</a></td></tr>
<tr><td class="yr">Spring 2024</td><td class="evlinks"></td></tr>
<tr><td class="yr">Summer 2023</td><td class="evlinks"><a href="/files/evals/eval-ta-econ100a-su2023.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=12">Instructor</a></td></tr>
<tr><td class="yr">Spring 2023</td><td class="evlinks"><a href="/files/evals/eval-ta-econ100a-sp2023.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=13">Instructor</a><br><span class="ab">(2 sections merged)</span></td></tr>

<tr><td rowspan="2" class="c-name">Applied Econometrics &amp; Data (ECON 121)</td><td rowspan="2">Econometrics</td><td class="yr">Fall 2023</td><td class="evlinks"><a href="/files/evals/eval-ta-econ121-fa2023.pdf">Student</a></td></tr>
<tr><td class="yr">Fall 2022</td><td class="evlinks"><a href="/files/evals/eval-ta-econ121-fa2022.pdf">Student</a> · <a href="/files/evals/instructor-evaluations-combined.pdf#page=14">Instructor</a></td></tr>

<tr><td class="c-name">Decisions under Uncertainty (ECON 171)</td><td>Microeconomics</td><td class="yr">Summer 2022</td><td class="evlinks"><a href="/files/evals/eval-ta-econ171-su2022.pdf">Student</a></td></tr>

<tr class="grp"><td colspan="4">University of British Columbia</td></tr>
<tr><td class="c-name">Microeconomic &amp; Macroeconomic Policy (ECON 210/211)</td><td>Economics</td><td class="yr">2018-2019</td><td class="evlinks"><a href="/files/evals/eval-ta-ubc-econ-2018-2019.pdf">Student</a></td></tr>
<tr><td rowspan="2" class="c-name">Human Geography: Globalization &amp; Environment (GEOG 121/122)</td><td rowspan="2">Geography</td><td class="yr">2018-2019</td><td class="evlinks"><a href="/files/evals/eval-ta-ubc-geog-2018-2019.pdf">Student</a></td></tr>
<tr><td class="yr">2015-2017</td><td class="evlinks"><a href="/files/evals/eval-ta-ubc-geog-2015-2017.pdf">Student</a></td></tr>

<tr class="grp"><td colspan="4">NRU Higher School of Economics</td></tr>
<tr><td class="c-name">Microeconomics, Mathematical Optimization, and Academic English (Grader)</td><td>Economics, mathematics &amp; English</td><td class="yr">2013-2014</td><td></td></tr>
</tbody>
</table>

<ol class="fnotes">
<li id="fn1">Each link opens the official student evaluation report for that course and term ("Student"), and the supervising professor's evaluation of my teaching ("Instructor").</li>
<li id="fn2">The instructor evaluation is optional, so one is not available for every section; every instructor evaluation that was made available to me is posted here.</li>
</ol>

## Guest lectures

<details markdown="1">
<summary>Guest lectures (2016-2025)</summary>

- Finding and using existing data for empirical research (ECON 190, *Introduction to Research in Economics*, Manu Vespa; 2024 and 2025)
- Urbanization, Access to Housing & Slums in Latin American Cities (GEOG 352, *Urbanization in the Global South*, Feb 2019)
- Introduction to Data Analysis (BIO 340, *Introduction to Cell Biology*, Mar 2018)
- Gentrification of "Hutongs" in Beijing, China (GEOG 350, *Urban Worlds*, Nov 2017)
- Vancouver Housing Market: Price Dynamics and Social Outcomes (GEOG 350, *Urban Geography*, Mar 2017)
- Land, Housing & Gentrification in Beijing, China (GEOG 352, *Urbanization in the Global South*, Feb 2017)
- Vancouver Housing Market: Evidence of a "Growth Machine" (GEOG 250, *Cities*, Nov 2016)

</details>

## Teaching credentials

<ul class="cred">
<li>Summer Graduate Teaching Scholars (SGTS) program (2024)</li>
<li>Advanced College Teaching: Equitable Course Design and Instruction (2023-2024)</li>
<li>Center for the Integration of Research, Teaching, and Learning (CIRTL) Associate (2021)</li>
<li>Certificate in Advanced Teaching &amp; Learning (CATL, 2016-2017)</li>
<li>Instructional Skills Workshop (ISW, 2016)</li>
</ul>
