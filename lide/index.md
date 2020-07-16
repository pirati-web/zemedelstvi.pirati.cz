<div class="row">
  <div class="columns">
    <div class="o-section">
      <div class="o-section-inner">
          <header class="c-page-header">
            <h1 itemprop="headline" class="c-page-title">Garant programového bodu</h1>
          </header>
          {% assign tag = 'garant'  %}
          <ul>
{% for staff_member in site.people %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
          </ul><hr><hr>
         {% assign posts=site.people %} 
         {% include articles/list-responsive.html posts=posts %}
         {% include articles/pagination.html paginator=paginator %}
      </div>
    </div>
  </div>
</div>
