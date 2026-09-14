---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
backdrop: true
---

{% include base_path %}

Education
======
* **Ph.D. in Economics**, Vienna University of Economics and Business (WU), Vienna — 2023 – present
  * Visiting Ph.D. researcher, Drexel University, School of Economics, Philadelphia, PA (Jan – May 2026)
* **M.Sc. in Economics**, Vienna University of Economics and Business (WU), Vienna — 2020 – 2023
* **B.Sc. in Economic and Social Sciences**, Vienna University of Economics and Business (WU), Vienna — 2015 – 2020

Work experience
======
* **Economist**, Austrian Institute of Economic Research (WIFO), Vienna — Sept 2023 – present
  * Research on the trade and macroeconomic effects of economic sanctions using structural gravity (PPML) methods; results published in *The World Economy* and *Perspektiven der Wirtschaftspolitik*.
  * Core member of the Global Sanctions Data Base (GSDB) team: primary data collection, sanctions coding, codebook documentation, and the reproducible data pipeline behind Releases 4 and 5, with a seven-author team across five institutions in four countries.
  * Member of the Research Centre International Economics (FIW).
  * Author of a commissioned assessment of European economic exposure to a reopening of Iran (wiiw Research Report 481).
  * Translate empirical findings into policy-facing analysis for Austrian and European audiences; work covered by CEPR/VoxEU, the *Frankfurter Allgemeine Zeitung*, and *profil*.

* **Lecturer**, Vienna University of Economics and Business (WU), Vienna — Oct 2024 – present
  * Design and teach the undergraduate course *Databases and Methods of Empirical Economic Research*: relational databases, SQL, and applied empirical workflows.

* **Visiting Researcher**, Drexel University, School of Economics, Philadelphia, PA — Jan – May 2026
  * Research stay hosted by the School of Economics; joint work on sanctions and gravity-based trade research with the Drexel team.

* **Researcher, International Economics Section**, Oesterreichische Nationalbank (OeNB, Austrian National Bank), Vienna — Jan – Aug 2023
  * Designed, built, and documented a database of globalization metrics and shipped it as an internal R Shiny application, replacing manual data requests for the analyst team.
  * Co-authored survey-based research on household attitudes toward green finance in Austria, published in the OeNB *Financial Stability Report*.

* **Data Analyst**, GoStudent, Vienna — Sept 2021 – Dec 2022
  * Analytics at a fast-paced EdTech start-up — Austria's second-largest unicorn — through a period of rapid growth.
  * Built and maintained the data pipelines, recurring reporting, and KPI dashboards used by commercial and operations teams; converted ad-hoc business questions into defined metrics and self-serve reporting.
  * Owned the analysis and redesign of payment process workflows, surfacing failure points and reducing manual intervention.
  * Presented analytical findings to non-technical stakeholders across commercial and operations teams.

* **IT Systems Administrator**, BAWAG P.S.K., Vienna — 2015 – June 2020
  * Maintained production systems and infrastructure at a major Austrian retail and commercial bank, alongside undergraduate studies — five years in a regulated financial-services environment.

Skills
======
* **Programming**: R, Python, SQL
* **Econometrics**: high-dimensional fixed-effects panel estimation, PPML / structural gravity models, dyadic panel data, survey analysis
* **Data and tools**: Power BI, Qlik Sense, Apache Superset, DBeaver, R Shiny, Git, Jira, LaTeX
* **Languages**: German (native), Arabic (native), English (C2, full professional proficiency)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
