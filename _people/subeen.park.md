---
layout: people
background: /assets/images/kaist.jpg
title: Subeen Park (박수빈)
---

{%- assign person_id = "subeen.park" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl }}/assets/images/people/subeen.park.jpg" alt="{{ person.name }}">

I am an **Undergraduate Student at [KAIST School of Computing](https://cs.kaist.ac.kr)**.

{% include person_contact.md person_id=person_id %}


{% include person_education.md person_id=person_id %}


#### Awards and Honors

- Dean's List, 2022 Spring

- 7th place, ACM International Collegiate Programming Contest (ICPC) Regional Contest---Seoul, 2021.

- 4th Prize, Samsung Collegiate Programming Cup (SCPC), 2021.