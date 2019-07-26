---
title: "Team"
layout: gridlay
excerpt: "Team members"
sitemap: false
permalink: /team/
---

## Faculty

{% assign number_printed = 0 %}
{% for member in site.data.team_faculty %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {{ member.email }}
  <br>{{ member.web }}
  <br>{{ member.since }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% if even_odd == 2 %}
</div>
{% endif %}

<br><br>

## External Visitors

{% assign number_printed = 0 %}
{% for member in site.data.team_visitors %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {{ member.email }}
  <br>{{ member.web }}
  <br>{{ member.since }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% if even_odd == 2 %}
</div>
{% endif %}

<br><br>

## Postdocs

{% assign number_printed = 0 %}
{% for member in site.data.team_postdocs %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {{ member.email }}
  <br>{{ member.web }}
  <br>{{ member.since }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% if even_odd == 2 %}
</div>
{% endif %}

<br><br>

## Postdocs and PhD Students

{% assign number_printed = 0 %}
{% for member in site.data.team_students %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {{ member.email }}
  <br>{{ member.web }}
  <br>{{ member.since }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% if even_odd == 2 %}
</div>
{% endif %}

<br><br>
## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.team_alumni %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{ member.info }}</i></h5>
  {{ member.email }}
  <br>{{ member.web }}
  <br>{{ member.since }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 2 %}
</div>
{% endif %}

