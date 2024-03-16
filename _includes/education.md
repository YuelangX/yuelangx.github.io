<h2 style="margin: 2px 0px -15px;">Education</h2>

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

