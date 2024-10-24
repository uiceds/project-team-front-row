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
  <meta name="dc.modified" content="2024-10-24T15:58:46+00:00" />
  <meta property="article:modified_time" content="2024-10-24T15:58:46+00:00" />
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
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-front-row/v/b2b45915d425f9dfff8d65fd268214e0f019bde2/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-front-row/v/b2b45915d425f9dfff8d65fd268214e0f019bde2/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-front-row/v/b2b45915d425f9dfff8d65fd268214e0f019bde2/manuscript.pdf" />
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
([permalink](https://uiceds.github.io/project-team-front-row/v/b2b45915d425f9dfff8d65fd268214e0f019bde2/))
was automatically generated
from [uiceds/project-team-front-row@b2b4591](https://github.com/uiceds/project-team-front-row/tree/b2b45915d425f9dfff8d65fd268214e0f019bde2)
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

| Column        | Description         | 
|:-----------------:|:-------------:|
| STATE | This data element identifies the state in which the crash occurred. The codes are from the General Services Administration’s (GSA) publication of worldwide Geographic Location Codes (GLC). |
| ST_CASE | This data element is the unique case number assigned to each crash. It appears on each data file and is used to merge information from the data files together. |
| VE_TOTAL | This data element is the number of contact motor vehicles that the officer reported on the PAR as a unit involved in the crash. |
| VE_FORMS | This data element is a count of all vehicle forms applicable to this crash. |
| PVH_INVL | This data element is the number of parked or working vehicles involved in the crash. |
| PEDS | This data element records the number of pedestrians involved in the crash. |
| PERNOTMVIT | This data element counts the number of persons not in motor vehicles in transport (non-motorists) involved in the crash. |
| PERMVIT | This data element counts the number of persons in motor vehicles in transport (motorists) involved in the crash. |
| PERSONS | This data element is a count of the total number of persons involved in the crash. |
| COUNTY | This data element identifies the county in which the crash occurred. |
| CITY | This data element identifies the city in which the crash occurred. |
| DAY | This data element records the day of the month on which the crash occurred. |
| MONTH | This data element records the month in which the crash occurred. |
| YEAR | This data element records the year in which the crash occurred. |
| DAY_WEEK | This data element identifies the day of the week on which the crash occurred. |
| HOUR | This data element records the hour when the crash occurred. |
| MINUTE | This data element records the minute when the crash occurred. |
| NHS | This data element identifies whether the crash occurred on a National Highway System (NHS) route. |
| RUR_URB | This data element identifies whether the crash occurred in a rural or urban area. |
| FUNC_SYS | This data element identifies the functional classification of the trafficway segment where the crash occurred. |
| RD_OWNER | This data element identifies the entity responsible for the ownership of the road where the crash occurred. |
| ROUTE | This data element records the type of route where the crash occurred, such as Interstate, U.S. Highway, or State Highway. |
| TWAY_ID | This data element identifies the primary trafficway on which the crash occurred. |
| TWAY_ID2 | This data element identifies the secondary trafficway associated with the crash, if applicable. |
| MILEPT | This data element records the milepoint nearest to the crash location. |
| LATITUDE | This data element identifies the location of the crash using latitude coordinates. |
| LONGITUD | This data element identifies the location of the crash using longitude coordinates. |
| SP_JUR | This data element identifies if the crash occurred in a special jurisdiction, such as military or Indian reservations. |
| HARM_EV | This data element records the first harmful event that occurred in the crash sequence. |
| MAN_COLL | This data element identifies the manner of collision, such as rear-end, head-on, or angle. |
| RELJCT1 | This data element identifies the relationship of the crash to a junction, such as intersection or non-intersection. |
| RELJCT2 | This data element provides additional information about the crash’s relationship to the junction. |
| TYP_INT | This data element identifies the type of intersection involved in the crash, if applicable. |
| WRK_ZONE | This data element identifies if the crash occurred in a work zone. |
| REL_ROAD | This data element identifies the relationship of the crash to the road, such as on the roadway or off the roadway. |
| LGT_COND | This data element identifies the light condition at the time of the crash, such as daylight, dark, or dusk. |
| WEATHER1 | This data element records the primary weather condition at the time of the crash. |
| WEATHER2 | This data element records the secondary weather condition at the time of the crash. |
| WEATHER | This data element identifies additional weather factors at the time of the crash. |
| SCH_BUS | This data element identifies if a school bus was involved in the crash. |
| RAIL | This data element identifies if the crash involved a rail system or crossing. |
| NOT_HOUR | This data element records the hour when the crash was reported to authorities. |
| NOT_MIN | This data element records the minute when the crash was reported to authorities. |
| ARR_HOUR | This data element records the hour when emergency services arrived at the scene. |
| ARR_MIN | This data element records the minute when emergency services arrived at the scene. |
| HOSP_HR | This data element records the hour when the injured were admitted to the hospital. |
| HOSP_MN | This data element records the minute when the injured were admitted to the hospital. |
| CF1, CF2, CF3 | These data elements record contributing factors to the crash, such as driver behaviors or environmental conditions. |
| FATALS | This data element records the number of fatalities resulting from the crash. |
| DRUNK_DR | This data element records whether a driver involved in the crash was suspected of drinking alcohol. |


Link: <https://www.kaggle.com/datasets/nhtsa/2015-traffic-fatalities>

#### Plan and Proposal
Using the FARS dataset we aim to understand the trends in traffic fatalities in a given year and what factors are affecting those trends. We will also look at how the different variables play a role in the severity of the accident and identify geographic regions that are more prone to accidents. The trends in traffic fatalities found through this project can be used to inform policy makers and ultimately decrease the number of traffic fatalities. 





## Analysis {.page_break_before}

#### Exploratory Data Analysis


#### Predictive Modeling





## References {.page_break_before}
National Highway Traffic Safety Administration. "2015 Traffic Fatalities." Kaggle, https://www.kaggle.com/datasets/nhtsa/2015-traffic-fatalities. Accessed 24 Oct. 2024.

National Highway Traffic Safety Administration. Fatality Analysis Reporting System (FARS) Analytical User's Manual 1975-2015. U.S. Department of Transportation, Aug. 2016.
<div id="refs"></div>


