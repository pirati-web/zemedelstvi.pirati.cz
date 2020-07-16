---
layout: members
title: Tým Zemědělství
description:  My jsme zemědělci, lesníci, rolníci, rybáři, myslivci, včelaří, zahrádkáři, piráti, pirátky, chovatelé.
keywords: zemědělci, lesníci, rolníci, rybáři, myslivci, včelaři, zahrádkáři, chovatelé, piráti, pirátky, příznivci
---

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
            <h2>{{ staff_member.name }} - {{ staff_member.description | markdownify}}</h2>
            <p><img src={{ staff_member.img  }}></p>
          {% endfor %}
          </ul><hr><hr>
         {% assign posts=site.people %} 
         {% include articles/list-responsive.html posts=posts %}
         {% include articles/pagination.html paginator=paginator %}
      </div>
    </div>
  </div>
</div>
