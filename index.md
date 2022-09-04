---
layout: default
title: "Home"
---

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.github.url }}/assets/img/jisungpark.jpg" alt="Jisung Park">

I am an Assistant Professor in the [Department of Computer Science and Engineering](https://cse.postech.ac.kr) at [POSTECH](https://www.postech.ac.kr). Before joining POSTECH, I was a Postdoctoral Research Associate and Lecturer in the [Department of Information Technology and Electrical Engineering (D-ITET)](https://ee.ethz.ch) at [ETH Zürich](https://www.ethz.ch), working in [SAFARI Research Group](https://safari.ethz.ch) led by [Prof. Onur Mutlu](https://people.inf.ethz.ch/omutlu). I earned my Ph.D. and B.S.E. degrees in Electrical Engineering and Computer Science from [Seoul National University (SNU)](https://www.snu.ac.kr). At SNU, I was a member of [Computer Architecture and Embedded Systems Laboratory (CARES)](https://cares.snu.ac.kr) led by [Prof. Jihong Kim](http://cares.snu.ac.kr/?module=Board&action=SiteBoard&sMode=VIEW_FORM&iBrdNo=1&iBrdContNo=84&sBrdContRe=0&sSearchField=&sSearchValue=&CurrentPage=1). My research interests lie in computer architecture, system software, memory systems, storage systems, system security, and hardware/software interaction.

<br>
#### Contact

- Email: [{{site.data.basic.email}}](mailto:{{site.data.basic.email}})
- Bibliography: [DBLP](https://dblp.uni-trier.de/pid/123/2642-1.html), [Google Scholar](https://scholar.google.com/citations?user=1qw7AosAAAAJ&hl=en)
- Phone: {{site.data.basic.phone}}
- Office: {{site.data.basic.office}}, {{site.data.basic.institution_address}}

#### Experience

{% for section in site.data.experience %} 
- {{section.position}}, {{section.institution}}, {{section.period}} {% endfor %}
