---
layout: default
categories: [prototype, assessment]
title: Assessment report
type: [prototype]
permalink: /prototype/assessment/
description: assessment report landing
body-class: assessments

cards:
  - title: Calls For Participation
    date: |
      120 characters max – ipsum suspendisse ultrices gravida dictum fusce ut placerat orci nulla
    link: "/"
    label: Find out More
  - title: Human Health
    date: September 20 
    time: 12 PM–1:30 PM CT
    download: |
      [Agenda](/) \| [ Flyer PDF]()
    link: "/"
    label: Register
  - title: Water
    date: September 22 
    time: 12 PM–1:30 PM CT
    download: |
      [Agenda](/) \| [ Flyer PDF]()
    link: "/"
    label: Register


tabs:
    - title: Overview
    - title: Mandate
    - title: Chapters
    - title: Roles
    - title: Leadership
    - title: Regions
    - title: Engagement
    - title: Workshops
    - title: FAQs
    - title: Timeline
---
# {{ page.title }}

 <div class="usa-alert usa-alert--info">
    <div class="usa-alert__body">
      <p class="usa-alert__text">
        Development of the Fifth National Climate Assessment (NCA5) is currently underway, with anticipated delivery in 2023. This content will be updated as new information becomes available.
      </p>
    </div>
  </div>


<ul class="tabs">
    {% for t in page.tabs %}
			<li class="tab"><label for="tab1">{{ t.title }}</label></li>
    {% endfor %}
</ul>


## Upcoming
{% include patterns/card/event-jk.md %}

<a href="/">View all events <i class="fa-solid fa-arrow-right-long"></i></a>

<div class="content-rap" markdown="1">
<div class="article" markdown="1">
## About NCA5

The Fifth National Climate Assessment (NCA5), currently in development, will analyze the impacts of global change in the United States.
 
The development of NCA5 is overseen by a Federal Steering Committee appointed by the Subcommittee on Global Change Research (SGCR) and comprising representatives from USGCRP agencies. NOAA, as the administrative agency for NCA5, is responsible for establishing procedures for the report, releasing Federal Register Notices, and certifying the report meets Information Quality Act and Evidence Act standards. 
 
The process is designed to be transparent and inclusive, offering multiple opportunities for public participation. As in previous assessments, NCA5 will undergo an extensive, multi-phase process of internal and external review from federal agency experts, the general public, and external peer review by a panel of experts established by the National Academies of Sciences, Engineering, and Medicine. This approach is designed to result in a report that is authoritative, timely, relevant, and policy neutral; valued by authors and users; accessible to the widest possible audience; and fully compliant with the GCRA and other applicable laws and policies.
</div>
<div class="related-resources" markdown="1">
<div class="link-list" markdown="1">
#### Previous Assesments
- link one
- link two
- link three
</div>
<div class="link-list" markdown="1">
#### Sustained Resources
- link one
- link two
- link three
</div>
<div>