<h2 style="margin: 2px 0px -15px;">Education</h2>

{% for link in site.data.education.main %}

<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <a href="{{ link.pdf }}">{{ link.title }}</a>
    PDF
    Code</div>
</div>

<br>

{% endfor %}

