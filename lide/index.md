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
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item is-active" data-accordion-item="">
                                  <a href="#garant" class="c-simple-accordion-title">GARANT PROGRAMOVÉHO BODU</a>
                                    <div id="garant" class="c-simple-accordion-content" data-tab-content="">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'garant'" | sort:"ordgarant" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item" data-accordion-item="">
                                    <a href="#snemovna" class="c-simple-accordion-title">POSLANCI A POSLANKYNĚ</a>
                                    <div id="snemovna" class="c-simple-accordion-content" data-tab-content="">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'poslanec'" | sort:"ordpsp" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ket"  class="c-simple-accordion-title"><hr><h1>Zlínský kraj</h1><hr></a>
                                    <div id="ket" class="c-simple-accordion-content" data-tab-content="">
                                        <div class="c-simple-accordion-content-block">
                                            <hr><h1>Zlínský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'zlínský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item" data-accordion-item="">
                                    <a href="#snemovna" class="c-simple-accordion-title">KETy</a>
                                  <div class="c-simple-accordion-content-block">
                                            <hr><h1>Kraj Vysočina</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'vysočina'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <hr><h1>Moravskoslezský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'moravskoslezský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Jihočeský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Plzeňský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'plzeňský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Ústecký kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'ústecký'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Karlovarský kraj</h1>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'karlovarský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Královéhradecký kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'hradec'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Jihomoravský kraj</h1>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihomoravský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <hr><h1>Liberecký kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'liberecký'"%}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Pardubický kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'pardubický'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Královéhradecký kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'královehradecký'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                       <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Středočeský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'středočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Hlavní město Praha</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'praha'" | sort:"ordpraha" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                  </div></li>
                            </ul>
                        </div>
                    </div>
                </main>
            </div>
        </section>
        <!-- /. o-section -->
    </div>
</div>
