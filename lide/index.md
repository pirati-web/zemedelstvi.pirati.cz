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
            {% assign garant = site.people | where: "category", "garant" %}
            <h1 itemprop="headline" class="c-page-title">{{ staff_member.name }}Garant programového bodu</h1>
          </header>
          <ul>
          {% for staff_member in site.people %}
            <p><img src="{{ staff_member.img }}"><b>{{ staff_member.name }}</b> - {{ staff_member.description | markdownify}}</p>
          {% endfor %}
          </ul><hr><hr>
      </div>
    </div>
  </div>
</div>
