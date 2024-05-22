---
layout: people
background: /assets/images/kaist.jpg
title: Tanapoom Sermchaiwong
excerpt: "Tanapoom Sermchaiwong's website"
---

{%- assign person_id = "tanapoom.sermchaiwong" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl }}/assets/images/people/tanapoom.sermchaiwong.jpg" alt="{{ person.name }}">

I am a research intern at [KAIST Concurrency and Parallelism Lab]({{ site.baseurl }}/).
My research interest is in Program Analysis, Compilers, HDL, AI Hardware.

{% include person_contact.md person_id=person_id %}

{% include person_education.md person_id=person_id %}

#### Experiences
- Internship, [Prosys Lab @ KAIST](https://prosys.kaist.ac.kr/), Jun.2023 - Feb.2024.
  
  (Exploring directed graybox fuzzing, static code pruning, parallelization of static analysis.)
