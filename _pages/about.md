---
layout: about
title: Vivek Gopalakrishnan
permalink: /
description: Biomedical Data Science @ <a href="http://bme.jhu.edu/" target="_blank">JHU BME</a>

profile:
  align: right
  image: prof_pic.jpg
  address: Nova Scotia, 2019

news: false
years: [2021, 2020, 2019]
social: true
---

I am a combined BS/MSE student in the Department of Biomedical Engineering at Johns Hopkins University.

My research focuses on developing machine learning methods to analyze multi-subject neuroimaging data (advised by [Dr. Joshua T. Vogelstein](https://jovo.me) and [Dr. Carey E. Priebe](https://www.ams.jhu.edu/~priebe/)).
Currently, I am developing statistical graph theory algorithms to perform biomarker discovery in network-valued maps of the brain.

I also lead a Design Team of undergraduate biomedical engineers (advised by [Dr. Elizabeth Logsdon](https://www.bme.jhu.edu/people/faculty/elizabeth-logsdon/) and [Dr. Rani Hasan](https://www.hopkinsmedicine.org/profiles/results/directory/profile/1571333/rani-hasan)). 
We are building a dynamic fusion image guidance system for minimally invasive heart surgery.

---

{: #publications}
### Selected Publications

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
