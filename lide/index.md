---
layout: default
title: Tým Zemědělství
description:  My jsme zemědělci, lesníci, rolníci, rybáři, myslivci, včelaří, zahrádkáři, piráti, pirátky, chovatelé.
keywords: zemědělci, lesníci, rolníci, rybáři, myslivci, včelaři, zahrádkáři, chovatelé, piráti, pirátky, příznivci
---
<div class="row o-section-block o-section-block--divided">
    <div class="medium-12 large-12 columns">
        <section class="o-section">
            <div class="o-section-inner">
                <main class="o-section-block">
                    <div class="c-BasicPage">
                        <div class="c-BasicPage-content">
                            {% comment %}
                            <div class="c-BasicPage-header c-BasicPage-header--horizontal c-BasicPage-header--horizontal--mobilestacked">
                                <h1 class="c-BasicPage__title"> Organizace </h1>
                                <div class="c-BasicPage__meta">
                                    <div class="c-BasicPage__meta-filters">
                                        <div class="c-BasicPage__meta-filter-block">
                                            <div class="c-BasicPage__meta-filters__title">Filtr</div>
                                        </div>
                                        <div class="c-BasicPage__meta-filter-block">
                                            <div class="c-BasicPage__meta-filter">
                                                <button class="c-BasicPage__meta-filter-btn" type="button" data-toggle="category-filters">Všechny kategorie</button>
                                                <div class="c-BasicPage__meta-filter-dropdown" id="category-filters" style="display: none; " data-toggler="is-open">
                                                    <ul>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="group1" value="">
                                                            <label for="group1">Garant programového bodu</label>
                                                        </li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="group6" value="">
                                                            <label for="group6">Poslanci a poslankyně</label>
                                                        </li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="group2" value="">
                                                            <label for="group2">Krajští experti</label>
                                                        </li>
                                                        <li class="spacer"></li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="group5" value="" checked="">
                                                            <label for="group5">Všechny kategorie</label>
                                                        </li>
                                                    </ul>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="c-BasicPage__meta-filter-block">
                                            <div class="c-BasicPage__meta-filter">
                                                <button class="c-BasicPage__meta-filter-btn" type="button" data-toggle="region-filters">Všechny kraje</button>
                                                <div class="c-BasicPage__meta-filter-dropdown" id="region-filters" style="display: none; " data-toggler="is-open">
                                                    <ul>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="region_group1" value="">
                                                            <label for="region_group1">Středočeský kraj</label>
                                                        </li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="region_group2" value="">
                                                            <label for="region_group2">Moravskoslezský kraj</label>
                                                        </li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="region_group3" value="">
                                                            <label for="region_group3">Zlínský kraj</label>
                                                        </li>
                                                        <li class="spacer"></li>
                                                        <li>
                                                            <input type="checkbox" name="group[]" id="region_group4" value="" checked="">
                                                            <label for="region_group4">Všechny kraje</label>
                                                        </li>
                                                    </ul>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            {% endcomment %}
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item is-active" data-accordion-item="">
                                    <a href="#garant" class="c-simple-accordion-title">Garant programového bodu</a>
                                    <div id="garant" class="c-simple-accordion-content" data-tab-content="">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'garant'" | sort:"ordgarant" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item" data-accordion-item="">
                                    <a href="#snemovna" class="c-simple-accordion-title">Poslanci a poslankyně</a>
                                    <div id="snemovna" class="c-simple-accordion-content" data-tab-content="">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'poslanec'" | sort:"ordpsp" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item" data-accordion-item="">
                                    <a href="#ket" class="c-simple-accordion-title">Krajští experti resortu</a>
                                    <div id="ket" class="c-simple-accordion-content" data-tab-content="">
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Zlínský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'zlínský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                      <div class="c-simple-accordion-content-block">
                                            <h3>Kraj Vysočina</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'vysočina'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Moravskoslezský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'moravskoslezský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Jihočeský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <h3>Plzeňský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'plzeňský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Ústecký kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'ústecký'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Karlovarský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'vary'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Královéhradecký kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'hradec'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <h3>Jihomoravský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihomoravský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Liberecký kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'liberecký'"%}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Pardubický kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'pardubický'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Královéhradecký kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'královehradecký'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <h3>Středočeský kraj</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'středočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <h3>Hlavní město Praha</h3>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'praha'" | sort:"ordpraha" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                  </div>

                                </li>
                            </ul>
                        </div>
                    </div>
                </main>
            </div>
        </section>
        <!-- /. o-section -->
    </div>
</div>
