---
layout: about
title: Vivek Gopalakrishnan
permalink: /
description: Biomedical Data Science @ <a href="https://hst.mit.edu/" target="_blank">Harvard-MIT</a>

profile:
  align: right
  image: prof_pic.jpg
  address: Nova Scotia, 2019

news: false
years: [2021, 2020, 2019]
social: true
---

I am an incoming PhD student in the Harvard-MIT Health Sciences and Technology Program.
I concentrate on the development of machine learning methods for complex problems in healthcare, with interest in applications to cardiovascular disease and algorithmic fairness.

I obtained BS and MSE from the Department of Biomedical Engineering at Johns Hopkins University in 2021.
My past research has focused on the development of machine learning methods to analyze multi-subject neuroimaging data (advised by [Dr. Joshua T. Vogelstein](https://jovo.me) and [Dr. Carey E. Priebe](https://www.ams.jhu.edu/~priebe/)). Most recently, I developed statistical graph theory algorithms to perform biomarker discovery in network-valued maps of the brain. I also led a Design Team of undergraduate biomedical engineers (advised by [Dr. Elizabeth Logsdon](https://www.bme.jhu.edu/people/faculty/elizabeth-logsdon/) and [Dr. Rani Hasan](https://www.hopkinsmedicine.org/profiles/results/directory/profile/1571333/rani-hasan)). 
We built a dynamic fusion image guidance system for minimally invasive heart surgery.

---

{: #publications}
### Selected Publications

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
