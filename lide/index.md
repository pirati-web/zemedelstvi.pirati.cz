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
                                    <a href="#snemovna" class="c-simple-accordion-title"><hr><h1>POSLANCI A POSLANKYNĚ</a>
                                    <div id="snemovna" class="c-simple-accordion-content" data-tab-content="">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'poslanec'" | sort:"ordpsp" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketzlinsky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - ZLÍNSKÝ KRAJ</h1><hr></a>
                                    <div id="ketzlinsky" class="c-simple-accordion-content" data-tab-content="">
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'zlínský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
                                    </div>
                                </li>
                            </ul>
                            <ul class="c-simple-accordion" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item" data-accordion-item="">
                                    <a href="#ketvysocina" class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - KRAJ VYSOČINA</h1><hr></a>
                                    <div id="ketvysocina" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'vysočina'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
								                    </div>	
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketmoravskoslezsky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - MORAVSKOSLEZSKÝ KRAJ</h1><hr></a>
                                    <div id="ketmoravskoslezsky" class="c-simple-accordion-content" data-tab-content="">								
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'moravskoslezský'" %}
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
