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
                                            <hr><h1>Kraj Vysočina</h1><hr>
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
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketjihocesky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - JIHOČESKÝ KRAJ</h1><hr></a>
									<div id="ketjihocesky" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
									</div>   
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketplzensky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - PLZEŇSKÝ KRAJ</h1><hr></a>                 
									<div id="ketplzensky" class="c-simple-accordion-content" data-tab-content="">	
                                       <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'plzeňský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
                                    </div>									   
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketplzensky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - ÚSTECKÝ KRAJ</h1><hr></a>
									<div id="ketplzensky" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'ústecký'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
									</div>	
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketkarlovarsky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - KARLOVARSKÝ KRAJ</h1><hr></a>
									<div id="ketkarlovarsky" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'karlovarský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
									</div>	
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketkarlovarsky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - KRÁLOVÉHRADECKÝ KRAJ</h1><hr></a>
									<div id="ketkarlovarsky" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'královéhradecký'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
									</div>   
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketjihomoravsky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - JIHOMORAVSKÝ KRAJ</h1><hr></a>
									<div id="ketjihomoravsky" class="c-simple-accordion-content" data-tab-content="">									
                                       <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Jihomoravský kraj</h1>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'jihomoravský'" %}
                                            {% include people/list-2col.html param=team %}
                                       </div>
									</div>   
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketliberecky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - LIBERECKÝ KRAJ</h1><hr></a>
									<div id="ketliberecky" class="c-simple-accordion-content" data-tab-content="">									
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'liberecký'"%}
                                            {% include people/list-2col.html param=team %}
                                        </div>
									</div>	
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketpardubicky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - PARDUBICKÝ KRAJ</h1><hr></a>
									<div id="ketpardubicky" class="c-simple-accordion-content" data-tab-content="">											
                                        <div class="c-simple-accordion-content-block">
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'pardubický'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
									</div>	
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ketstredocesky"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - STŘEDOČESKÝ KRAJ</h1><hr></a>
									<div id="ketstredocesky" class="c-simple-accordion-content" data-tab-content="">										
                                        <div class="c-simple-accordion-content-block">
                                            <br><br><hr><h1>Středočeský kraj</h1><hr>
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'středočeský'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>
									</div>   
                                </li>
                            </ul>
                            <ul class="c-simple-accordion  content-block" data-accordion="" data-options="allowAllClosed: true">
                                <li class="c-simple-accordion-item  content-block" data-accordion-item="">
                                    <a href="#ket"  class="c-simple-accordion-title"><hr><h1>EXPERTI RESORTU - HLAVNÍ MĚSTO PRAHA</h1><hr></a>
									<div id="ketstredocesky" class="c-simple-accordion-content" data-tab-content="">
                                        <div class="c-simple-accordion-content-block">
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
