---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Currently a PhD Candidate at McGill University studying the Head-Direction system in freely-moving mice :compass: :mouse2: Specialising in electrophysiology and calcium imaging and skilled in data analysis and visualization using Python. I am conscientious and self-motivated with sound critical thinking and decision-making skills.

<div class="row">
<div class = "column" style= "text-align:left; margin-right:2%; margin-bottom:2%">
{% include about/skills.html title="<i>in vivo </i> Electrophysiology" source=site.data.ephys-skills %}
<div style="margin-left:4%">
Chronic silicon probe implant<br>
Chronic tetrode implant <br>
Optogenetic manipulations <br>
Freely-moving recordings <br>
Head-fixed recordings <br>
Sleep recordings
</div>
</div>

<div class = "column" style= "text-align:left; margin-right: 2%; margin-bottom:2%">
{% include about/skills.html title="<i>in vivo </i> Calcium Imaging" source=site.data.ca2-skills %}
<div style="margin-left:4%">
Viral injections & GRIN lens implant <br>
1-photon Miniscope longitudinal recordings <br>
UCLA V4 Miniscope assembly 
</div>
</div>
</div>

<div class="row">
<div class = "column" style= "text-align:left; margin-right:2%; margin-bottom:2%">
{% include about/skills.html title="Python Skills" source=site.data.programming-skills %}
<div style="margin-left:7%">
Matplotlib
<br>
Numpy
<br>
Pandas
</div>
</div>

<div class = "column" style = "text-align:left; margin-right:1%; margin-bottom:2%">
{% include about/skills.html title="Languages &#127757;" source=site.data.languages %}
</div>
</div>


<!--
<div class="row">
{% include about/skills.html title="<i>in vivo</i> Electrophysiology" source=site.data.ephys-skills %}
{% include about/skills.html title="<i>in vivo</i> Calcium Imaging" source=site.data.ca2-skills %}
</div>



<font size = '5'>
<strong>Languages &#127757; </strong>
</font>
<br>
Spanish (fluent)
<br>
English (fluent)
<br>
French (Intermediate/Advanced)
</div>

</div>
-->
<div class="row">
{% include about/timeline.html %}
</div>
