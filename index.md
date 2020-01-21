---
title: 'Recruiting the Out-of-State University'
subtitle: 'Off-Campus Recruiting by Public Research Universities'
author: Ozan Jaquette
# lib_cdn: 'https://cdn.rawgit.com/ramnathv/slidifyLibraries/master/inst/libraries'
mode: selfcontained
ext_widgets : {rCharts: [libraries/leaflet]}
framework: revealjs
revealjs:
  theme: custom
  transition: slide
  center: 'false'
bibliography: ./assets/other/spencer-bib.bib
csl: ./assets/other/apa.csl

--- #title



# Recruiting the Out-of-State University
## Off-Campus Recruiting by Public Research Universities

<p class='author'>Ozan Jaquette</p>
<p class='affiliation'>University of California, Los Angeles</p>

<img id='logo_ucla' src='assets/images/ucla.png' alt='University of California, Los Angeles' />

<a id='link_presentation' href='https://ozanj.github.io/cerpp_2020/' target='_blank'>ozanj.github.io/cerpp_2020</a>

---

# Motivation
## Policy discourse about access to public research universities

The problem: access to public research universities
- Historical mission of social mobility for meritorious state residents
- Concern about growing socioeconomic and racial inequality in access
<br>
Mainstream policy discourse about access: The 2014 White House "Access Summit" 
- The White House (2014) review of causes of unequal college access
    - "achievement gap", "under-matching"; place responsibility on students, K-12 schools
    - affordability; declining state support leads to rising tuition prices
- The White House (2014) asks universities for *Commitments to Action on College Opportunity*
    - Universities pledge "action plans" (e.g., need-based financial aid, "outreach", holistic admission)

<br>
Problem with policy discourse: does not interrogate university enrollment priorities
- Applauds universities for commitment to access despite "deficiencies" of students and K-12 schools, despite declines in state funding
- Decades of research finds policy adoption a symbolic effort to appease stakeholders (e.g., Davis, 2005)

---

# Motivation
## Analyze recruiting to understand university enrollment priorities

Alternative explanation for access inequality
- University enrollment priorities biased against poor students and/or communities of color

Why study university recruiting behavior
- Universities expend substantial resources identifying and recruiting prospects (Ruffalo Noel-Levitz, 2018)
- Internal resource allocation better indicator of organizational priorities than rhetoric, policies
- Knowing which student populations targeted by recruiting efforts indicates enrollment priorities

Research focus
- Analyze off-campus recruiting visits (e.g., visit to a local high school) by public research universities as a means of gaining insight about university enrollment priorities
- **Research question**
    - What are the similarities and differences in off-campus recruiting patterns across universities?
- **Analytic focus**
    - Income; race; academic achievement; in-state vs. out-of-state

--- &twocol

# Background
## The enrollment management industry

*** =left

**The enrollment funnel**

<img src="assets/images/funnel.png" alt="Enrollment Funnel" style="width:80%;float:left;">

*** =right

**Interventions along the funnel**
* Identify prospects
    - Buy "student lists" from College Board/ACT
* Recruit prospects remotely
    * Email, mail, text, etc.
* Recruit prospects in-person
    * **Off-campus recruiting visits** (e.g., high school visits, college fairs)
    * Campus visits
    * Other "outreach"
* Solicit inquiries, stealth applicants
    * Social media, advertising
* Convert admits to enrollees
    * Financial aid leveraging

---

# Data and Methods
## Summary of Data Collection Sources and Quality Checks Performed

<div class="table-wrapper">
  <div class="scroll-wrapper scroll-wrapper-x">
<table class="appendix-table">         <thead>             <tr>             <th class="blank"></th>     <th class="bold">NC State</th> <th class="bold">Rutgers</th> <th class="bold">Stony Brook</th> <th class="bold">Alabama</th> <th class="bold">Arkansas</th> <th class="bold">UC Berkeley</th> <th class="bold">UC Irvine</th> <th class="bold">UC Riverside</th> <th class="bold">UC San Diego</th> <th class="bold">Cincinnati</th> <th class="bold">CU Boulder</th> <th class="bold">Georgia</th> <th class="bold">Kansas</th> <th class="bold">UMass</th> <th class="bold">Nebraska</th> <th class="bold">Pittsburgh</th> <th class="bold">S.Carolina</th>              </tr>         </thead>         <tbody>     <tr><td class="blank bold">Web-scrape data collection</td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="indent">Scraped data on off-campus recruiting events?</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr> <tr><td class="indent">Manually checked each scraped event?</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr> <tr><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="blank bold">Public records request data collection</td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="indent">Requested data from Enrollment Management VP from university?</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr> <tr><td class="indent">Received data from Enrollment Management VP?</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td></tr> <tr><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="indent">State law allows nonresidents to request from public universities?</td><td>Y</td><td>N</td><td>Y</td><td>Ambiguous</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td></tr> <tr><td class="indent">Made public records request to university?</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr> <tr><td class="indent">Received public records data from university (by 10/1/2019)?</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>-</td><td>Y</td><td>Y</td><td>Y</td><td>-</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td></tr> <tr><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="indent">Manually checked each visit from requested data?</td><td>N</td><td>Y</td><td>Y</td><td>-</td><td>-</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>-</td><td>-</td><td>Y</td></tr> <tr><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="blank bold">Data used in report analyses</td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td><td class="blank"></td></tr> <tr><td class="indent">Web-scrape data is primary data source?</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td></tr> <tr><td class="indent">Public records data used as primary data source?</td><td class="col-width">N</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">N</td><td class="col-width">N</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">Y</td><td class="col-width">N</td><td class="col-width">N</td><td class="col-width">Y</td></tr>          </tbody>     </table>
  </div>
</div>

--- #references
# References
## &nbsp;

<p><a id='bib-RN2436'></a><a href="#cite-RN2436">[1]</a><cite>
G. F. Davis.
&ldquo;Firms and environments&rdquo;.
In: 
<em>The handbook of economic sociology</em>.
Ed. by N. J. Smelser and R. Swedberg.
New York: Russell Sage Foundation, 2005, pp. 478-502.
ISBN: 0691034486 (alk. paper).</cite></p>

<p><a id='bib-RN4402'></a><a href="#cite-RN4402">[2]</a><cite>
Ruffalo Noel-Levitz.
<em>2018 marketing and student recruitment report of effective practices</em>.
Tech. rep.
Ruffalo Noel-Levitz, 2018.
URL: <a href="http://learn.ruffalonl.com/rs/395-EOG-977/images/RNL_2018_Student_Recruitment_Marketing_Report_EM-19.pdf">http://learn.ruffalonl.com/rs/395-EOG-977/images/RNL_2018_Student_Recruitment_Marketing_Report_EM-19.pdf</a>.</cite></p>

<p><a id='bib-RN4017'></a><a href="#cite-RN4017">[3]</a><cite>
The White House.
<em>Commitments to action on college opportunity</em>.
Tech. rep.
The Executive Office of the President, 2014.</cite></p>

<p><a id='bib-RN4016'></a><a href="#cite-RN4016">[4]</a><cite>
The White House.
<em>Increasing college opportunity for low-income students</em>.
Tech. rep.
The Executive Office of the President, 2014.</cite></p>
