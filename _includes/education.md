<h2 style="margin: 2px 0px -15px;">Education</h2>

{% for link in site.data.education.main %}

<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=50;height=20%">
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <a href="{{ link.pdf }}">{{ link.title }}</a>
    <div>PDF</div>
    <div>PDF</div>
  </div>
</div>

<br>

{% endfor %}

