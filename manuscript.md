---
title: Analysis of Traffic Fatality Records
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-10-24'
author-meta:
- Justin Rebholz
- Cameron Kimber
- Hannah Daggett
- Riley Kelch
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Analysis of Traffic Fatality Records" />
  <meta name="citation_title" content="Analysis of Traffic Fatality Records" />
  <meta property="og:title" content="Analysis of Traffic Fatality Records" />
  <meta property="twitter:title" content="Analysis of Traffic Fatality Records" />
  <meta name="dc.date" content="2024-10-24" />
  <meta name="citation_publication_date" content="2024-10-24" />
  <meta property="article:published_time" content="2024-10-24" />
  <meta name="dc.modified" content="2024-10-24T15:30:35+00:00" />
  <meta property="article:modified_time" content="2024-10-24T15:30:35+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Justin Rebholz" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Illinois" />
  <meta name="citation_author" content="Cameron Kimber" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Illinois" />
  <meta name="citation_author" content="Hannah Daggett" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Illinois" />
  <meta name="citation_author" content="Riley Kelch" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Illinois" />
  <link rel="canonical" href="https://uiceds.github.io/project-team-front-row/" />
  <meta property="og:url" content="https://uiceds.github.io/project-team-front-row/" />
  <meta property="twitter:url" content="https://uiceds.github.io/project-team-front-row/" />
  <meta name="citation_fulltext_html_url" content="https://uiceds.github.io/project-team-front-row/" />
  <meta name="citation_pdf_url" content="https://uiceds.github.io/project-team-front-row/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://uiceds.github.io/project-team-front-row/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-front-row/v/85da1417b2b2bbd1cbddcd8ac2c2e0746e6060b2/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-front-row/v/85da1417b2b2bbd1cbddcd8ac2c2e0746e6060b2/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-front-row/v/85da1417b2b2bbd1cbddcd8ac2c2e0746e6060b2/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://uiceds.github.io/project-team-front-row/v/85da1417b2b2bbd1cbddcd8ac2c2e0746e6060b2/))
was automatically generated
from [uiceds/project-team-front-row@85da141](https://github.com/uiceds/project-team-front-row/tree/85da1417b2b2bbd1cbddcd8ac2c2e0746e6060b2)
on October 24, 2024.
</em></small>



## Authors



+ **Justin Rebholz**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jrebholz12](https://github.com/jrebholz12)
    <br>
  <small>
     Department of Civil and Environmental Engineering, University of Illinois
  </small>

+ **Cameron Kimber**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ckimber2](https://github.com/ckimber2)
    <br>
  <small>
     Department of Civil and Environmental Engineering, University of Illinois
  </small>

+ **Hannah Daggett**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [hed2](https://github.com/hed2)
    <br>
  <small>
     Department of Civil and Environmental Engineering, University of Illinois
  </small>

+ **Riley Kelch**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [rileykelch](https://github.com/rileykelch)
    <br>
  <small>
     Department of Civil and Environmental Engineering, University of Illinois
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/uiceds/project-team-front-row/issues)
or email to
Justin Rebholz \<rebholz4@illinois.edu\>, 
Cameron Kimber \<ckimber2@illinois.edu\>, 
Hannah Daggett \<hed2@illinois.edu\>, 
Riley Kelch \<rjkelch2@illinois.edu\>.


:::


## Abstract {.page_break_before}

#### Description
The dataset that will be used for this project is the Fatality Analysis Reporting System created by the National Highway Safety Administration. The data will be obtained from the NHTSA’s FARS database, which is publicly accessible.The FARS dataset is available in the CSV format. The specific dataset that our project will be focused on is labeled "accidents" and includes 32K+ instances and 52 columns. The columns descriptions are described in the Fatality Analysis Reporting System (FARS) Analytical User’s Manual 1975-2015. Columns are described in the below table:

| *Column Abbreviation* | Description         | 
|:-----------------|:-------------:|
| State | This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). |
| ST_CASE | This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. |
| VE_TOTAL | This data element is the number of contact motor vehicles that the officer reported on the PAR as a unit involved in the crash.|

Link: <https://www.kaggle.com/datasets/nhtsa/2015-traffic-fatalities>

#### Plan and Proposal
Using the FARS dataset we aim to understand the trends in traffic fatalities in a given year and what factors are affecting those trends. We will also look at how the different variables play a role in the severity of the accident and identify geographic regions that are more prone to accidents. The trends in traffic fatalities found through this project can be used to inform policy makers and ultimately decrease the number of traffic fatalities. 







