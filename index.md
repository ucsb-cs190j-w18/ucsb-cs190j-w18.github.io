---
title: CS190J, Winter 2018, pconrad, dmirza
---

# {{site.course}}, {{site.quarter}}


<div id="info" data-role="collapsible" data-collapsed="false">
<h2>Course Information</h2>
<ul>
{% for item in site.info %}
<li><a href="{{item.url}}"  data-ajax="false">{{item.title }}</a></li>
{% endfor %}
</ul>
</div>

<div id="papers" data-role="collapsible" data-collapsed="true">
<h2>Papers</h2>
<ul>
{% for item in site.papers %}
<li><a href="{{item.url}}"  data-ajax="false">{{item.num }}</a>&mdash;{{item.desc}}</li>
{% endfor %}
</ul>
</div>


<div data-role="collapsible" data-collapsed="false">
<h2 id="homework">Homework:</h2>
{% include hwk_table.html %}
</div>


<div data-role="collapsible" data-collapsed="false">
<h2 id="teams">Lectures</h2>
{%include lectures_table.html %}
</div>
