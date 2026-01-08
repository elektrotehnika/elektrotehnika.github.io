---
title: "Center for Integrated Systems (CIS) - Team"
layout: gridlay
excerpt: "Center for Integrated Systems (CIS): Team members"
sitemap: false
permalink: /team/
---

# Group Members

**We are looking for new self-motivated PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**

<!-- Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors). -->

Jump to [Faculty](#faculty), [PhD students](#phd-students), [Master students](#master-students), [alumni](#alumni) and [administrative support](#administrative-support).<!-- , [lab visitors](#lab-visitors). -->

<hr>

<!-- Faculty -->
## Faculty

<div class="row align-items-center">
  <div class="col-md-2 col-sm-2 vertical-align">
  <div style="max-width: 200px; text-align: center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/VMdbap.jpg" class="img-responsive" style="width: 100%" />
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4>Vladimir M. Milovanović</h4>
  Associate Professor, Department of EECS<br>
  University of Kragujevac, Sestre Janjić 6, 34000 Kragujevac, Serbia<br>
  Office: A-G-13 - Faculty of Engineering<br>
  Dipl.-Ing. (<a href="https://www.etf.bg.ac.rs/en">ETF-BG</a>), Ph.D. (<a href="https://www.tudelft.nl/en/eemcs">TU Delft-EWI</a>)<br>
  <a href="https://milovanovic.github.io/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-webpage.png" height=25px></a>
  <a href="mailto:vlada@kg.ac.rs"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-email.png" height=25px></a>
  <a href="{{ site.url }}{{ site.baseurl }}/resumes/twhuang_cv.pdf"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-cv.png" height=25px></a>
  <a href="https://scholar.google.com/citations?user=ewvjbhgAAAAJ"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-scholar.jpg" height=25px></a>
  <a href="https://github.com/milovanovic"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-github.jpg" height=25px></a>
  </div>
</div>

<div class="row align-items-center">
  <div class="col-md-12 col-sm-12 vertical-align">
  <p><span class="badge badge-dark">Bio</span> Vladimir M. Milovanović received the Dipl.-Ing. degree in [Electrical Engineering](https://www.etf.bg.ac.rs/en) from the [University of Belgrade](https://www.bg.ac.rs/), Belgrade, Serbia in 2005, and the Ph.D. degree from the [Delft University of Technology](https://www.tudelft.nl/), Delft, the Netherlands, in 2010.</p>

  <p>Since the beginning of 2014, he was working as a Postdoctoral Scholar with the [University of California, Berkeley](https://www.berkeley.edu/). Before joining [Berkeley Wireless Research Center](https://bwrc.eecs.berkeley.edu/), from 2011 he was with [Vienna University of Technology](https://www.tuwien.at/en), Vienna, Austria as a Postdoctoral Research Fellow. Presently, he is holding a position of an Associate Professor with the Department of Electrical Engineering and Computer Sciences at the [Faculty of Engineering](https://www.fin.kg.ac.rs/en/), [University of Kragujevac](https://en.kg.ac.rs/), Serbia.<!--, and serves as the managing director of the Center for Integrated Systems within the same institution.--></p>

  <!--<p>He is a founder and managing director of one Stealth-Mode Start-Up Company.</p>-->

  <p>Dr. Milovanović has also held advisory, consulting, or visiting positions with Texas Instruments, NXP Semiconductors, Infineon Technologies, Sony and Broadcom.</p>

  <p>His research focuses and interests include design, modeling and optimization of analog, mixed-signal and digital integrated circuits and systems, along with the development and implementation of efficient artificial intelligence and signal processing algorithms.</p>

  <p>Prof. Milovanović is the recipient of the Best Student Paper Award at the 2009 IEEE Bipolar/BiCMOS Circuits and Technology Meeting and the Best Paper Awards at the 2014 IEEE International Conference on Microelectronics and the 2024 IcETRAN.</p>
  </div>
</div>

<hr>

<!-- Graduate Students -->
## Graduate Students

<hr>

<!-- PhD students -->
### PhD Students

<!-- истраживачи-сарадници -->
<!-- #### Research Assistants -->
<!-- N/A -->

<!-- истраживачи-приправници -->
#### Junior Research Assistants (JRAs)
{% assign number_printed = 0 %}
{% for member in site.data.JrResAsst %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>{{ member.status }}<br>e-mail: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

<hr>

<!-- асистенти -->
#### Teaching Assistants (TAs)
<!-- Isidora Grujić -->

<hr>

<!-- Marija Petrović -->
<!-- Aleksandar Kondić -->
<!-- Dušan Obradović -->
<!-- Dejan Rakić -->
<!-- etc. -->

<hr>

<!-- MSc students -->
### Master Students
{% assign number_printed = 0 %}
{% for member in site.data.StudentsMSc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>{{ member.status }}<br>e-mail: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<hr>

<!-- сарадници у настави -->
<!-- #### Junior Teaching Assistants -->
<!-- N/A -->

<hr>

<!-- Undergraduate Students -->
## Undergraduate Students
<!-- Filip Milić -->

<hr>

## Open Positions!

<p>We are looking for new *self-driven* and *highly motivated* PhD, MSc, and undergraduate students joining us, doing research on **Integrated Circuit (IC) & System-on-Chip (SoC) Design**, and **Artificial Intelligence & Machine Learning (AI & ML)**.
Please <a href="mailto:vlada@kg.ac.rs">e-mail Prof. Milovanović</a> your résumé (curriculum vitae) together with a cover letter in which you would state your research interests (see our [Research](/research) and [Why Join Our Team?](#why-join-our-team)).</p>

<hr>

<!-- Staff -->
<!-- ## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>-->
<!--  <i>{{ member.info }}--> <!--<br>email: <{{ member.email }}></i> -->
<!--   <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4> -->
<!--  <i>{{ member.info }}--> <!-- <br>email: <{{ member.email }}></i> -->
<!--   <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>

<hr> -->

## Administrative Support

{% assign number_printed = 0 %}
{% for member in site.data.admin_assistants %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p>We are looking for a full-time or a part-time <a href="https://en.wikipedia.org/wiki/Administrative_assistant">administrative assistant</a> for our group. If you believe you are a *reliable*, *responsible*, and *well-organized* secretary candidate, please <a href="mailto:vlada@kg.ac.rs">contact Prof. Milovanović</a> by sending your CV/résumé and motivation letter.</p>
