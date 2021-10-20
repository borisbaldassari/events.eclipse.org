---
title: "Cloud Native for Eclipse Foundation Day"
headline: "Cloud Native for <br/> Eclipse Foundation Day 2021"
subtitle: "Exploring the Eclipse Open Source Ecosystem for Kubernetes and Cloud Native Development"
tagline: "Virtual Conference | October 11, 2021"
date: 2021-10-11T12:00:00-04:00
hide_page_title: true
hide_sidebar: true
header_wrapper_class: "header-cn4ef-day-2021-event"
jumbotron_tagline_class: "col-sm-18 col-sm-offset-3"
custom_jumbotron_class: " "
hide_breadcrumb: true
container: "container-fluid"
summary: "Cloud Native for Eclipse Foundation (CN4EF) Day 2021 is a full-day of expert talks, demos, and thought-provoking sessions focused on enterprise applications implemented using Eclipse Foundation projects on Kubernetes -- from the cloud and all the way to the edge. The Eclipse Cloud Development Tools, Jakarta EE, MicroProfile, and Eclipse Edge Native communities will all be represented. CN4CF Day is co-located with KubeCon / CloudNativeCon North America 2021."
layout: single
custom_jumbotron: '
<a class="btn btn-primary register-btn" href="#agenda">Agenda</a>
<a class="btn btn-primary register-btn" href="#speakers">Speakers</a>
<ul class="list-inline cn4ef-logos">
<li data-mh="asd"><a href="https://ecdtools.eclipse.org/"><img src="images/logos/ecd-tools.png"></a></li>
<li data-mh="asd"><a href="https://edgenative.eclipse.org/"><img src="images/logos/edge-native.png"></a></li>
<li data-mh="asd"><a href="https://jakarta.ee"><img src="images/logos/jakarta-ee.png"></a></li>
<li data-mh="asd"><a href="https://microprofile.io/workinggroup/"><img src="images/logos/microprofile.png"></a></li>
</ul>
'
footer_class: "footer-darker"
---

{{< cn4ef-day/about-the-event >}}

<!-- Add user carousel for speaker -->
{{< grid/section-container id="speakers" class="featured-section-row text-center featured-section-row-dark-bg eclipsefdn-user-display-circle" >}}
  {{< events/user_display event="cn4ef-day" year="2021" title="Speakers" source="speakers" imageRoot="/2021/cn4ef-day/images/speakers/" subpage="speakers" displayLearnMore="false" />}}
{{</ grid/section-container >}}

<!-- Add Agenda -->
{{< grid/section-container id="agenda" class="featured-section-row featured-section-row-light-bg" >}}
  {{< events/agenda event="cn4ef-day" year="2021" >}}
{{</ grid/section-container >}}
{{< bootstrap/modal id="eclipsefdn-modal-event-session" >}}

{{< cn4ef-day/event-hosted-by >}}