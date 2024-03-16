<h2 style="margin: 2px 0px -15px;">Education</h2>

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:25%;vertical-align:middle;border:none" align="center">
<img width="80" src="../images/tsinghua.png"/> 
</td>
<td style="padding:20px;width:75%;vertical-align:middle;border: none" align="left">
Ph.D. Student. Sep. 2020 - Jun. 2025<br>
Department of Automation<br>
Tsinghua University<br>
</td>
</tr>
  
{% for link in site.data.education.main %}

<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    <img src="{{ link.image }}" style="width=25;height=25">
  </div>
  <div style="position: relative;padding-right: 15px;padding-left: 20px;">
    {{ link.title }}
    {{ link.title }}
    {{ link.title }}
  </div>
</div>

<br>

{% endfor %}

