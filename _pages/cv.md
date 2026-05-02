---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* **Ph.D. in Economics and Finance (DEPAP)**, Catholic University of Milan, Italy
* **M.Sc. in Economics**, University Milan-Bicocca, Italy
* **BA in Political Economy**, University of Bergamo, Italy

---

## Experience

### Senior Research Associate & Senior Research Fellow
*University of Oxford, United Kingdom | 09/2024 – 09/2026*

### Senior Economist
*Whiteshield Advisory, Dubai | 06/2023 – 09/2024*

### Senior Data Scientist
*Whiteshield Advisory, Dubai | 11/2021 – 06/2023*

### Researcher
*Fondazione Eni Enrico Mattei, Milan | 06/2021 – 01/2022*

### Postdoctoral Researcher
*Bamberg University, Germany | 10/2019 – 04/2021*

### Research Intern
*Central Bank of Ireland, Dublin | 10/2018 – 10/2019*

### Research Assistant
*City, University of London | 11/2017 – 02/2018*

---

## Skills
* **Programming:** Matlab, Python, R, Stata
* **Languages:** English (fluent), German (beginner), Italian (native)

---

## Research
<ul>
  {% for post in site.research %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

---

## Policy
{% for post in site.policy reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Teaching
<ul>
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>