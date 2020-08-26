---
layout: communal-elections
title: Chce to změnu
heroBgImg: articles/2020/kampan20/zahajenikampan.jpg
campaignGroupUid: volby-2020
campaignCategoryUid: kraj2020
candidateListUid: kraj2020
hideCandidateSocialProfiles: true
# customizeHeader: true
---
{% assign candidates = site.candidatelists | where: "uid", page.candidateListUid | first %}
<!-- {% capture mainContent %}
  <h1 class="head-alt-lg md:head-alt-xl text-center">Krajské volby 2020</h1>
{% endcapture %} -->

<!-- {% capture subContent %}
  <h2 class="head-alt-base md:head-alt-md mt-2 text-center">Šance <strong>změnit budoucnost</strong></h2>
{% endcapture %} -->

<!-- {% include elections-header.html img=page.img bgImg=page.heroBgImg mainContent=mainContent subContent=subContent candidateListNumber=candidates.number %} -->

<h2 class="head-alt-base md:head-alt-md mt-2">Krajské volby 2020</h2>
<div class="mt-4 md:mt-8 space-y-4">
  {% include buttons/icon.html icon="ico--chevron-right" href="/volby-2020/povolebni-strategie-2020.pdf" cta="Povolební strategie" class="btn--cyan-200 btn--hoveractive btn--fullwidth md:btn--autowidth text-lg" %}
  {% include buttons/icon.html icon="ico--chevron-right" href="/volby-2020/zlk-kodex-2020.pdf" cta="Kodex kandidáta" class="btn--blue-300 btn--hoveractive btn--fullwidth md:btn--autowidth text-lg" %}
</div>
